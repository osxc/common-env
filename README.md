common-env
==========

Prepares a common environment to avoid altering hundreds of dotfiles to change your shell environment.

[![Build Status](https://travis-ci.org/osxc/common-env.svg)](https://travis-ci.org/osxc/common-env/)

## Requirements

- Needs root if you want to affect other users

## Role variables

| Name                  | Description                                      | Default            |
|-----------------------|--------------------------------------------------|--------------------|
| `affected_users`      | The users using the common env                   | `[ "{{ ansible_user_id }}" ]` |

## Dependencies

none

## License

MIT

## Author

- Robin Ricard
