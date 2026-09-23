# SWITCH-CONTROLLED-PWM-AND-GIT-VERSION-CONTROL

## AIM:
To analyse switch-controlled PWM operation by varying LED brightness through predefined duty-cycle levels and to implement source-code version control using Git.

---

## Apparatus Required

| S. No. | Apparatus / Software | Specification |
|:---:|---|---|
| 1 | Development Board | PWM and GPIO supported |
| 2 | LED | Standard LED |
| 3 | Resistor | Current limiting |
| 4 | Push-Button Switch | Digital input |
| 5 | Pull-up/Pull-down Resistor | As required |
| 6 | Jumper Wires | Circuit connection |
| 7 | USB Cable | Programming and communication |
| 8 | Computer/Laptop | Windows |
| 9 | VS Code | Source code and Git management |
| 10 | Git | Version control |
| 11 | GitHub/GitLab | Remote repository |
| 12 | Microcontroller IDE/SDK | Required development environment |

---

## Procedure

1. Connect the LED to a PWM-supported GPIO pin.
2. Connect the push-button switch to a suitable digital input pin.
3. Configure the PWM module and switch input.
4. Develop the program to vary LED brightness through 0%, 25%, 50%, 75%, and 100% duty cycles for successive switch presses.
5. After reaching 100%, reverse the sequence from 100% to 75%, 50%, 25%, and 0%.
6. Build and compile the program.
7. Flash the program to the development board.
8. Press the switch successively and observe the corresponding LED brightness levels.
9. Verify the forward and reverse brightness sequence.
10. Open the project in VS Code and stage the verified source code using Git.
11. Commit the changes with an appropriate commit message.
12. Push the commit to the remote Git repository.
13. Verify the updated source code in the remote repository.

---

## PWM Configuration

| Parameter | Configuration |
|---|---|
| PWM Output | LED GPIO |
| PWM Frequency | As configured |
| Duty Cycle Sequence | 0% → 25% → 50% → 75% → 100% |
| Reverse Sequence | 100% → 75% → 50% → 25% → 0% |
| Input | Push-Button Switch |
| Control Method | Switch-Controlled PWM |

---

## Git Configuration

| Operation | Tool / Command |
|---|---|
| Source Code Review | VS Code |
| Staging | Git |
| Commit | Git |
| Remote Repository | GitHub/GitLab |
| Push | Git |
| Version Management | Git |

---

## OUTPUT
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/e305eaa1-1f1a-4731-9856-9ccd4541576c" />

---

## Result

The switch-controlled PWM program was successfully developed and tested. The LED brightness was varied through 0%, 25%, 50%, 75%, and 100%, followed by the reverse sequence. The verified source code was successfully committed and pushed to the remote Git repository.
