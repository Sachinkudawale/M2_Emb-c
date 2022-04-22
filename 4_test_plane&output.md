# Test Plan
## High Level Test Plan

| Test ID| Description | Exp I/P | Exp O/P | Status |
| -------| ----------- | ------- | ------- | ------ |
| H_01 | DEVELOPMENT OF .elf file    | .C file | .elf| Implemented |
| H_02 | Cross Compilation of Files  | Converting .c file into target output | .elf or .hex using win-avr   | Implemented |
| H_03 | Search components in Simulide |  Components  | Assembling     | Implemented  |
| H_04 | Door sensor  |      Run     | led blink    | Implemented |

## Low Level Test Plan

| Test ID| Description | Exp I/P | Exp O/P | Status |
| -------| ----------- | ------- | ------- | ------ |
| L_01 | door close  | switch off | whenever required | Implemented |
| L_02 | door close| switch on | whenever required | Implemented |
