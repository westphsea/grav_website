---
title: register
form:
    fields:
        -
            name: username
            type: text
            validate:
                required: true
                message: PLUGIN_LOGIN.USERNAME_NOT_VALID
                config-pattern@: system.username_regex
        -
            name: email
            type: text
            validate:
                required: true
                message: PLUGIN_LOGIN.EMAIL_VALIDATION_MESSAGE
        -
            name: password1
            type: password
            label: 'Enter a password'
            validate:
                required: true
                message: PLUGIN_LOGIN.PASSWORD_VALIDATION_MESSAGE
                config-pattern@: system.pwd_regex
        -
            name: password2
            type: password
            label: 'Repeat the password'
            validate:
                required: true
                message: PLUGIN_LOGIN.PASSWORD_VALIDATION_MESSAGE
                config-pattern@: system.pwd_regex
    buttons:
        -
            type: submit
            value: Submit
        -
            type: reset
            value: Reset
    process:
        register_user: true
        display: /home
        message: 'Welcome to my site!'
---

