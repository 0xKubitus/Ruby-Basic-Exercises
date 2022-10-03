<div align="center">

# Ruby-Exercises
Une série d'exercices pour découvrir la programmation en Ruby.

<br/>



![Ubuntu package](https://img.shields.io/static/v1?logo=ubuntu&label=Ubuntu&message=22.04&color=orange)

[![THP Badge](https://raw.githubusercontent.com/Beygs/Beygs/main/assets/the-hacking-project-badge.svg)](https://www.thehackingproject.org/)

[![forthebadge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMzcuMTg5OTk5OTk5OTk5OTciIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAyMzcuMTg5OTk5OTk5OTk5OTcgMzUiPjxyZWN0IGNsYXNzPSJzdmdfX3JlY3QiIHg9IjAiIHk9IjAiIHdpZHRoPSIxMzQuMDc5OTk5OTk5OTk5OTgiIGhlaWdodD0iMzUiIGZpbGw9IiMyMjIyMjIiLz48cmVjdCBjbGFzcz0ic3ZnX19yZWN0IiB4PSIxMzIuMDc5OTk5OTk5OTk5OTgiIHk9IjAiIHdpZHRoPSIxMDUuMTA5OTk5OTk5OTk5OTkiIGhlaWdodD0iMzUiIGZpbGw9IiNGNUY1RjUiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTYuMjUgMTQuNjZMMTMuNjEgMTQuNjZMMTMuNjEgMTMuNDdMMjAuMzggMTMuNDdMMjAuMzggMTQuNjZMMTcuNzIgMTQuNjZMMTcuNzIgMjJMMTYuMjUgMjJMMTYuMjUgMTQuNjZaTTI1LjYyIDIyTDI0LjE0IDIyTDI0LjE0IDEzLjQ3TDI1LjYyIDEzLjQ3TDI1LjYyIDE3LjAyTDI5LjQzIDE3LjAyTDI5LjQzIDEzLjQ3TDMwLjkxIDEzLjQ3TDMwLjkxIDIyTDI5LjQzIDIyTDI5LjQzIDE4LjIxTDI1LjYyIDE4LjIxTDI1LjYyIDIyWk00MS4yMyAyMkwzNS42NSAyMkwzNS42NSAxMy40N0w0MS4xOSAxMy40N0w0MS4xOSAxNC42NkwzNy4xMyAxNC42NkwzNy4xMyAxNy4wMkw0MC42NCAxNy4wMkw0MC42NCAxOC4xOUwzNy4xMyAxOC4xOUwzNy4xMyAyMC44Mkw0MS4yMyAyMC44Mkw0MS4yMyAyMlpNNTIuODggMjJMNTEuNDAgMjJMNTEuNDAgMTMuNDdMNTIuODggMTMuNDdMNTIuODggMTcuMDJMNTYuNzAgMTcuMDJMNTYuNzAgMTMuNDdMNTguMTcgMTMuNDdMNTguMTcgMjJMNTYuNzAgMjJMNTYuNzAgMTguMjFMNTIuODggMTguMjFMNTIuODggMjJaTTYzLjY5IDIyTDYyLjE1IDIyTDY1LjM4IDEzLjQ3TDY2LjcxIDEzLjQ3TDY5LjkzIDIyTDY4LjM5IDIyTDY3LjY5IDIwLjAxTDY0LjM5IDIwLjAxTDYzLjY5IDIyWk02Ni4wNCAxNS4yOEw2NC44MCAxOC44Mkw2Ny4yNyAxOC44Mkw2Ni4wNCAxNS4yOFpNNzMuNjIgMTguMTlMNzMuNjIgMTguMTlMNzMuNjIgMTcuMzlRNzMuNjIgMTYuMTkgNzQuMDUgMTUuMjdRNzQuNDcgMTQuMzUgNzUuMjcgMTMuODVRNzYuMDcgMTMuMzUgNzcuMTIgMTMuMzVMNzcuMTIgMTMuMzVRNzguNTQgMTMuMzUgNzkuNDAgMTQuMTJRODAuMjYgMTQuODkgODAuNDAgMTYuMjlMODAuNDAgMTYuMjlMNzguOTIgMTYuMjlRNzguODIgMTUuMzcgNzguMzkgMTQuOTZRNzcuOTYgMTQuNTUgNzcuMTIgMTQuNTVMNzcuMTIgMTQuNTVRNzYuMTYgMTQuNTUgNzUuNjQgMTUuMjZRNzUuMTIgMTUuOTYgNzUuMTEgMTcuMzNMNzUuMTEgMTcuMzNMNzUuMTEgMTguMDlRNzUuMTEgMTkuNDcgNzUuNjAgMjAuMjBRNzYuMTAgMjAuOTIgNzcuMDUgMjAuOTJMNzcuMDUgMjAuOTJRNzcuOTMgMjAuOTIgNzguMzcgMjAuNTNRNzguODEgMjAuMTQgNzguOTIgMTkuMjJMNzguOTIgMTkuMjJMODAuNDAgMTkuMjJRODAuMjcgMjAuNTkgNzkuMzkgMjEuMzVRNzguNTEgMjIuMTIgNzcuMDUgMjIuMTJMNzcuMDUgMjIuMTJRNzYuMDMgMjIuMTIgNzUuMjYgMjEuNjNRNzQuNDggMjEuMTUgNzQuMDYgMjAuMjZRNzMuNjQgMTkuMzcgNzMuNjIgMTguMTlaTTg2LjE5IDIyTDg0LjcxIDIyTDg0LjcxIDEzLjQ3TDg2LjE5IDEzLjQ3TDg2LjE5IDE3LjQ3TDg3LjAxIDE2LjQ2TDg5LjUxIDEzLjQ3TDkxLjMwIDEzLjQ3TDg4LjEzIDE3LjI1TDkxLjQ4IDIyTDg5LjczIDIyTDg3LjE2IDE4LjMxTDg2LjE5IDE5LjM0TDg2LjE5IDIyWk05Ni44MyAyMkw5NS4zNSAyMkw5NS4zNSAxMy40N0w5Ni44MyAxMy40N0w5Ni44MyAyMlpNMTAzLjEyIDIyTDEwMS42NCAyMkwxMDEuNjQgMTMuNDdMMTAzLjEyIDEzLjQ3TDEwNi45NCAxOS41NEwxMDYuOTQgMTMuNDdMMTA4LjQxIDEzLjQ3TDEwOC40MSAyMkwxMDYuOTIgMjJMMTAzLjEyIDE1Ljk1TDEwMy4xMiAyMlpNMTEyLjkwIDE4LjEzTDExMi45MCAxOC4xM0wxMTIuOTAgMTcuNDZRMTEyLjkwIDE1LjUzIDExMy44MyAxNC40NFExMTQuNzUgMTMuMzUgMTE2LjQxIDEzLjM1TDExNi40MSAxMy4zNVExMTcuODMgMTMuMzUgMTE4LjY3IDE0LjA1UTExOS41MSAxNC43NiAxMTkuNjggMTYuMDhMMTE5LjY4IDE2LjA4TDExOC4yMyAxNi4wOFExMTcuOTggMTQuNTQgMTE2LjQ0IDE0LjU0TDExNi40NCAxNC41NFExMTUuNDQgMTQuNTQgMTE0LjkzIDE1LjI2UTExNC40MSAxNS45OCAxMTQuMzkgMTcuMzdMMTE0LjM5IDE3LjM3TDExNC4zOSAxOC4wMlExMTQuMzkgMTkuNDAgMTE0Ljk3IDIwLjE3UTExNS41NiAyMC45MyAxMTYuNTkgMjAuOTNMMTE2LjU5IDIwLjkzUTExNy43MyAyMC45MyAxMTguMjEgMjAuNDJMMTE4LjIxIDIwLjQyTDExOC4yMSAxOC43NUwxMTYuNDUgMTguNzVMMTE2LjQ1IDE3LjYyTDExOS42OSAxNy42MkwxMTkuNjkgMjAuODlRMTE5LjIyIDIxLjUwIDExOC40MCAyMS44MVExMTcuNTggMjIuMTIgMTE2LjU0IDIyLjEyTDExNi41NCAyMi4xMlExMTUuNDcgMjIuMTIgMTE0LjY0IDIxLjYzUTExMy44MSAyMS4xNCAxMTMuMzcgMjAuMjRRMTEyLjkyIDE5LjMzIDExMi45MCAxOC4xM1oiIGZpbGw9IiNGNUY1RjUiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTQ4LjY1IDIyTDE0Ni4yNyAyMkwxNDYuMjcgMTMuNjBMMTUwLjExIDEzLjYwUTE1MS4yNSAxMy42MCAxNTIuMDkgMTMuOThRMTUyLjkzIDE0LjM1IDE1My4zOSAxNS4wNlExNTMuODQgMTUuNzYgMTUzLjg0IDE2LjcxTDE1My44NCAxNi43MVExNTMuODQgMTcuNjYgMTUzLjM5IDE4LjM1UTE1Mi45MyAxOS4wNSAxNTIuMDkgMTkuNDJRMTUxLjI1IDE5LjgwIDE1MC4xMSAxOS44MEwxNTAuMTEgMTkuODBMMTQ4LjY1IDE5LjgwTDE0OC42NSAyMlpNMTQ4LjY1IDE1LjQ3TDE0OC42NSAxNy45M0wxNDkuOTcgMTcuOTNRMTUwLjcwIDE3LjkzIDE1MS4wNyAxNy42MVExNTEuNDQgMTcuMjkgMTUxLjQ0IDE2LjcxTDE1MS40NCAxNi43MVExNTEuNDQgMTYuMTIgMTUxLjA3IDE1LjgwUTE1MC43MCAxNS40NyAxNDkuOTcgMTUuNDdMMTQ5Ljk3IDE1LjQ3TDE0OC42NSAxNS40N1pNMTYwLjk3IDIyTDE1OC42MCAyMkwxNTguNjAgMTMuNjBMMTYyLjQ0IDEzLjYwUTE2My41OCAxMy42MCAxNjQuNDIgMTMuOThRMTY1LjI2IDE0LjM1IDE2NS43MiAxNS4wNlExNjYuMTcgMTUuNzYgMTY2LjE3IDE2LjcxTDE2Ni4xNyAxNi43MVExNjYuMTcgMTcuNjIgMTY1Ljc0IDE4LjMwUTE2NS4zMiAxOC45OCAxNjQuNTMgMTkuMzZMMTY0LjUzIDE5LjM2TDE2Ni4zNCAyMkwxNjMuNzkgMjJMMTYyLjI3IDE5Ljc3TDE2MC45NyAxOS43N0wxNjAuOTcgMjJaTTE2MC45NyAxNS40N0wxNjAuOTcgMTcuOTNMMTYyLjI5IDE3LjkzUTE2My4wMyAxNy45MyAxNjMuNDAgMTcuNjFRMTYzLjc3IDE3LjI5IDE2My43NyAxNi43MUwxNjMuNzcgMTYuNzFRMTYzLjc3IDE2LjEyIDE2My40MCAxNS43OVExNjMuMDMgMTUuNDcgMTYyLjI5IDE1LjQ3TDE2Mi4yOSAxNS40N0wxNjAuOTcgMTUuNDdaTTE3MC41MyAxNy44MEwxNzAuNTMgMTcuODBRMTcwLjUzIDE2LjU1IDE3MS4xNCAxNS41NVExNzEuNzQgMTQuNTYgMTcyLjgwIDE0LjAwUTE3My44NyAxMy40MyAxNzUuMjAgMTMuNDNMMTc1LjIwIDEzLjQzUTE3Ni41MyAxMy40MyAxNzcuNTkgMTQuMDBRMTc4LjY1IDE0LjU2IDE3OS4yNiAxNS41NVExNzkuODcgMTYuNTUgMTc5Ljg3IDE3LjgwTDE3OS44NyAxNy44MFExNzkuODcgMTkuMDUgMTc5LjI2IDIwLjA0UTE3OC42NSAyMS4wNCAxNzcuNTkgMjEuNjBRMTc2LjUzIDIyLjE3IDE3NS4yMCAyMi4xN0wxNzUuMjAgMjIuMTdRMTczLjg3IDIyLjE3IDE3Mi44MCAyMS42MFExNzEuNzQgMjEuMDQgMTcxLjE0IDIwLjA0UTE3MC41MyAxOS4wNSAxNzAuNTMgMTcuODBaTTE3Mi45MyAxNy44MEwxNzIuOTMgMTcuODBRMTcyLjkzIDE4LjUxIDE3My4yMyAxOS4wNVExNzMuNTMgMTkuNjAgMTc0LjA1IDE5LjkwUTE3NC41NiAyMC4yMCAxNzUuMjAgMjAuMjBMMTc1LjIwIDIwLjIwUTE3NS44MyAyMC4yMCAxNzYuMzUgMTkuOTBRMTc2Ljg3IDE5LjYwIDE3Ny4xNiAxOS4wNVExNzcuNDYgMTguNTEgMTc3LjQ2IDE3LjgwTDE3Ny40NiAxNy44MFExNzcuNDYgMTcuMDkgMTc3LjE2IDE2LjU0UTE3Ni44NyAxNiAxNzYuMzUgMTUuNzBRMTc1LjgzIDE1LjQwIDE3NS4yMCAxNS40MEwxNzUuMjAgMTUuNDBRMTc0LjU2IDE1LjQwIDE3NC4wNCAxNS43MFExNzMuNTMgMTYgMTczLjIzIDE2LjU0UTE3Mi45MyAxNy4wOSAxNzIuOTMgMTcuODBaTTE4My41MiAyMC45M0wxODMuNTIgMjAuOTNMMTg0LjgxIDE5LjQwUTE4NS40OCAyMC4yNyAxODYuMjUgMjAuMjdMMTg2LjI1IDIwLjI3UTE4Ni4yNiAyMC4yNyAxODYuMjYgMjAuMjdMMTg2LjI2IDIwLjI3UTE4Ni43OCAyMC4yNyAxODcuMDUgMTkuOTZRMTg3LjMyIDE5LjY1IDE4Ny4zMiAxOS4wNUwxODcuMzIgMTkuMDVMMTg3LjMyIDE1LjQ0TDE4NC40MiAxNS40NEwxODQuNDIgMTMuNjBMMTg5LjY3IDEzLjYwTDE4OS42NyAxOC45MVExODkuNjcgMjAuNTQgMTg4Ljg1IDIxLjM2UTE4OC4wMyAyMi4xNyAxODYuNDMgMjIuMTdMMTg2LjQzIDIyLjE3UTE4NS41MSAyMi4xNyAxODQuNzUgMjEuODVRMTg0LjAwIDIxLjUzIDE4My41MiAyMC45M1pNMjAxLjUwIDIyTDE5NC43NiAyMkwxOTQuNzYgMTMuNjBMMjAxLjM1IDEzLjYwTDIwMS4zNSAxNS40NEwxOTcuMTIgMTUuNDRMMTk3LjEyIDE2Ljg1TDIwMC44NSAxNi44NUwyMDAuODUgMTguNjNMMTk3LjEyIDE4LjYzTDE5Ny4xMiAyMC4xN0wyMDEuNTAgMjAuMTdMMjAxLjUwIDIyWk0yMDUuODggMTcuODBMMjA1Ljg4IDE3LjgwUTIwNS44OCAxNi41NCAyMDYuNDggMTUuNTRRMjA3LjA4IDE0LjU1IDIwOC4xMyAxMy45OVEyMDkuMTggMTMuNDMgMjEwLjUwIDEzLjQzTDIxMC41MCAxMy40M1EyMTEuNjUgMTMuNDMgMjEyLjU4IDEzLjg0UTIxMy41MCAxNC4yNSAyMTQuMTEgMTUuMDJMMjE0LjExIDE1LjAyTDIxMi42MCAxNi4zOVEyMTEuNzkgMTUuNDAgMjEwLjYyIDE1LjQwTDIxMC42MiAxNS40MFEyMDkuOTQgMTUuNDAgMjA5LjQwIDE1LjcwUTIwOC44NyAxNiAyMDguNTcgMTYuNTRRMjA4LjI4IDE3LjA5IDIwOC4yOCAxNy44MEwyMDguMjggMTcuODBRMjA4LjI4IDE4LjUxIDIwOC41NyAxOS4wNVEyMDguODcgMTkuNjAgMjA5LjQwIDE5LjkwUTIwOS45NCAyMC4yMCAyMTAuNjIgMjAuMjBMMjEwLjYyIDIwLjIwUTIxMS43OSAyMC4yMCAyMTIuNjAgMTkuMjJMMjEyLjYwIDE5LjIyTDIxNC4xMSAyMC41OFEyMTMuNTAgMjEuMzUgMjEyLjU4IDIxLjc2UTIxMS42NSAyMi4xNyAyMTAuNTAgMjIuMTdMMjEwLjUwIDIyLjE3UTIwOS4xOCAyMi4xNyAyMDguMTMgMjEuNjFRMjA3LjA4IDIxLjA1IDIwNi40OCAyMC4wNVEyMDUuODggMTkuMDYgMjA1Ljg4IDE3LjgwWk0yMjAuNDQgMTUuNDhMMjE3Ljg2IDE1LjQ4TDIxNy44NiAxMy42MEwyMjUuMzggMTMuNjBMMjI1LjM4IDE1LjQ4TDIyMi44MSAxNS40OEwyMjIuODEgMjJMMjIwLjQ0IDIyTDIyMC40NCAxNS40OFoiIGZpbGw9IiMyMjIyMjIiIHg9IjE0NS4wNzk5OTk5OTk5OTk5OCIvPjwvc3ZnPg==)](https://forthebadge.com)

[![forthebadge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMzcuMTg5OTk5OTk5OTk5OTciIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAyMzcuMTg5OTk5OTk5OTk5OTcgMzUiPjxyZWN0IGNsYXNzPSJzdmdfX3JlY3QiIHg9IjAiIHk9IjAiIHdpZHRoPSIxMzQuMDc5OTk5OTk5OTk5OTgiIGhlaWdodD0iMzUiIGZpbGw9IiMxODE3MTciLz48cmVjdCBjbGFzcz0ic3ZnX19yZWN0IiB4PSIxMzIuMDc5OTk5OTk5OTk5OTgiIHk9IjAiIHdpZHRoPSIxMDUuMTA5OTk5OTk5OTk5OTkiIGhlaWdodD0iMzUiIGZpbGw9IiNGNUY1RjUiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTYuMjUgMTQuNjZMMTMuNjEgMTQuNjZMMTMuNjEgMTMuNDdMMjAuMzggMTMuNDdMMjAuMzggMTQuNjZMMTcuNzIgMTQuNjZMMTcuNzIgMjJMMTYuMjUgMjJMMTYuMjUgMTQuNjZaTTI1LjYyIDIyTDI0LjE0IDIyTDI0LjE0IDEzLjQ3TDI1LjYyIDEzLjQ3TDI1LjYyIDE3LjAyTDI5LjQzIDE3LjAyTDI5LjQzIDEzLjQ3TDMwLjkxIDEzLjQ3TDMwLjkxIDIyTDI5LjQzIDIyTDI5LjQzIDE4LjIxTDI1LjYyIDE4LjIxTDI1LjYyIDIyWk00MS4yMyAyMkwzNS42NSAyMkwzNS42NSAxMy40N0w0MS4xOSAxMy40N0w0MS4xOSAxNC42NkwzNy4xMyAxNC42NkwzNy4xMyAxNy4wMkw0MC42NCAxNy4wMkw0MC42NCAxOC4xOUwzNy4xMyAxOC4xOUwzNy4xMyAyMC44Mkw0MS4yMyAyMC44Mkw0MS4yMyAyMlpNNTIuODggMjJMNTEuNDAgMjJMNTEuNDAgMTMuNDdMNTIuODggMTMuNDdMNTIuODggMTcuMDJMNTYuNzAgMTcuMDJMNTYuNzAgMTMuNDdMNTguMTcgMTMuNDdMNTguMTcgMjJMNTYuNzAgMjJMNTYuNzAgMTguMjFMNTIuODggMTguMjFMNTIuODggMjJaTTYzLjY5IDIyTDYyLjE1IDIyTDY1LjM4IDEzLjQ3TDY2LjcxIDEzLjQ3TDY5LjkzIDIyTDY4LjM5IDIyTDY3LjY5IDIwLjAxTDY0LjM5IDIwLjAxTDYzLjY5IDIyWk02Ni4wNCAxNS4yOEw2NC44MCAxOC44Mkw2Ny4yNyAxOC44Mkw2Ni4wNCAxNS4yOFpNNzMuNjIgMTguMTlMNzMuNjIgMTguMTlMNzMuNjIgMTcuMzlRNzMuNjIgMTYuMTkgNzQuMDUgMTUuMjdRNzQuNDcgMTQuMzUgNzUuMjcgMTMuODVRNzYuMDcgMTMuMzUgNzcuMTIgMTMuMzVMNzcuMTIgMTMuMzVRNzguNTQgMTMuMzUgNzkuNDAgMTQuMTJRODAuMjYgMTQuODkgODAuNDAgMTYuMjlMODAuNDAgMTYuMjlMNzguOTIgMTYuMjlRNzguODIgMTUuMzcgNzguMzkgMTQuOTZRNzcuOTYgMTQuNTUgNzcuMTIgMTQuNTVMNzcuMTIgMTQuNTVRNzYuMTYgMTQuNTUgNzUuNjQgMTUuMjZRNzUuMTIgMTUuOTYgNzUuMTEgMTcuMzNMNzUuMTEgMTcuMzNMNzUuMTEgMTguMDlRNzUuMTEgMTkuNDcgNzUuNjAgMjAuMjBRNzYuMTAgMjAuOTIgNzcuMDUgMjAuOTJMNzcuMDUgMjAuOTJRNzcuOTMgMjAuOTIgNzguMzcgMjAuNTNRNzguODEgMjAuMTQgNzguOTIgMTkuMjJMNzguOTIgMTkuMjJMODAuNDAgMTkuMjJRODAuMjcgMjAuNTkgNzkuMzkgMjEuMzVRNzguNTEgMjIuMTIgNzcuMDUgMjIuMTJMNzcuMDUgMjIuMTJRNzYuMDMgMjIuMTIgNzUuMjYgMjEuNjNRNzQuNDggMjEuMTUgNzQuMDYgMjAuMjZRNzMuNjQgMTkuMzcgNzMuNjIgMTguMTlaTTg2LjE5IDIyTDg0LjcxIDIyTDg0LjcxIDEzLjQ3TDg2LjE5IDEzLjQ3TDg2LjE5IDE3LjQ3TDg3LjAxIDE2LjQ2TDg5LjUxIDEzLjQ3TDkxLjMwIDEzLjQ3TDg4LjEzIDE3LjI1TDkxLjQ4IDIyTDg5LjczIDIyTDg3LjE2IDE4LjMxTDg2LjE5IDE5LjM0TDg2LjE5IDIyWk05Ni44MyAyMkw5NS4zNSAyMkw5NS4zNSAxMy40N0w5Ni44MyAxMy40N0w5Ni44MyAyMlpNMTAzLjEyIDIyTDEwMS42NCAyMkwxMDEuNjQgMTMuNDdMMTAzLjEyIDEzLjQ3TDEwNi45NCAxOS41NEwxMDYuOTQgMTMuNDdMMTA4LjQxIDEzLjQ3TDEwOC40MSAyMkwxMDYuOTIgMjJMMTAzLjEyIDE1Ljk1TDEwMy4xMiAyMlpNMTEyLjkwIDE4LjEzTDExMi45MCAxOC4xM0wxMTIuOTAgMTcuNDZRMTEyLjkwIDE1LjUzIDExMy44MyAxNC40NFExMTQuNzUgMTMuMzUgMTE2LjQxIDEzLjM1TDExNi40MSAxMy4zNVExMTcuODMgMTMuMzUgMTE4LjY3IDE0LjA1UTExOS41MSAxNC43NiAxMTkuNjggMTYuMDhMMTE5LjY4IDE2LjA4TDExOC4yMyAxNi4wOFExMTcuOTggMTQuNTQgMTE2LjQ0IDE0LjU0TDExNi40NCAxNC41NFExMTUuNDQgMTQuNTQgMTE0LjkzIDE1LjI2UTExNC40MSAxNS45OCAxMTQuMzkgMTcuMzdMMTE0LjM5IDE3LjM3TDExNC4zOSAxOC4wMlExMTQuMzkgMTkuNDAgMTE0Ljk3IDIwLjE3UTExNS41NiAyMC45MyAxMTYuNTkgMjAuOTNMMTE2LjU5IDIwLjkzUTExNy43MyAyMC45MyAxMTguMjEgMjAuNDJMMTE4LjIxIDIwLjQyTDExOC4yMSAxOC43NUwxMTYuNDUgMTguNzVMMTE2LjQ1IDE3LjYyTDExOS42OSAxNy42MkwxMTkuNjkgMjAuODlRMTE5LjIyIDIxLjUwIDExOC40MCAyMS44MVExMTcuNTggMjIuMTIgMTE2LjU0IDIyLjEyTDExNi41NCAyMi4xMlExMTUuNDcgMjIuMTIgMTE0LjY0IDIxLjYzUTExMy44MSAyMS4xNCAxMTMuMzcgMjAuMjRRMTEyLjkyIDE5LjMzIDExMi45MCAxOC4xM1oiIGZpbGw9IiNGNUY1RjUiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTQ4LjY1IDIyTDE0Ni4yNyAyMkwxNDYuMjcgMTMuNjBMMTUwLjExIDEzLjYwUTE1MS4yNSAxMy42MCAxNTIuMDkgMTMuOThRMTUyLjkzIDE0LjM1IDE1My4zOSAxNS4wNlExNTMuODQgMTUuNzYgMTUzLjg0IDE2LjcxTDE1My44NCAxNi43MVExNTMuODQgMTcuNjYgMTUzLjM5IDE4LjM1UTE1Mi45MyAxOS4wNSAxNTIuMDkgMTkuNDJRMTUxLjI1IDE5LjgwIDE1MC4xMSAxOS44MEwxNTAuMTEgMTkuODBMMTQ4LjY1IDE5LjgwTDE0OC42NSAyMlpNMTQ4LjY1IDE1LjQ3TDE0OC42NSAxNy45M0wxNDkuOTcgMTcuOTNRMTUwLjcwIDE3LjkzIDE1MS4wNyAxNy42MVExNTEuNDQgMTcuMjkgMTUxLjQ0IDE2LjcxTDE1MS40NCAxNi43MVExNTEuNDQgMTYuMTIgMTUxLjA3IDE1LjgwUTE1MC43MCAxNS40NyAxNDkuOTcgMTUuNDdMMTQ5Ljk3IDE1LjQ3TDE0OC42NSAxNS40N1pNMTYwLjk3IDIyTDE1OC42MCAyMkwxNTguNjAgMTMuNjBMMTYyLjQ0IDEzLjYwUTE2My41OCAxMy42MCAxNjQuNDIgMTMuOThRMTY1LjI2IDE0LjM1IDE2NS43MiAxNS4wNlExNjYuMTcgMTUuNzYgMTY2LjE3IDE2LjcxTDE2Ni4xNyAxNi43MVExNjYuMTcgMTcuNjIgMTY1Ljc0IDE4LjMwUTE2NS4zMiAxOC45OCAxNjQuNTMgMTkuMzZMMTY0LjUzIDE5LjM2TDE2Ni4zNCAyMkwxNjMuNzkgMjJMMTYyLjI3IDE5Ljc3TDE2MC45NyAxOS43N0wxNjAuOTcgMjJaTTE2MC45NyAxNS40N0wxNjAuOTcgMTcuOTNMMTYyLjI5IDE3LjkzUTE2My4wMyAxNy45MyAxNjMuNDAgMTcuNjFRMTYzLjc3IDE3LjI5IDE2My43NyAxNi43MUwxNjMuNzcgMTYuNzFRMTYzLjc3IDE2LjEyIDE2My40MCAxNS43OVExNjMuMDMgMTUuNDcgMTYyLjI5IDE1LjQ3TDE2Mi4yOSAxNS40N0wxNjAuOTcgMTUuNDdaTTE3MC41MyAxNy44MEwxNzAuNTMgMTcuODBRMTcwLjUzIDE2LjU1IDE3MS4xNCAxNS41NVExNzEuNzQgMTQuNTYgMTcyLjgwIDE0LjAwUTE3My44NyAxMy40MyAxNzUuMjAgMTMuNDNMMTc1LjIwIDEzLjQzUTE3Ni41MyAxMy40MyAxNzcuNTkgMTQuMDBRMTc4LjY1IDE0LjU2IDE3OS4yNiAxNS41NVExNzkuODcgMTYuNTUgMTc5Ljg3IDE3LjgwTDE3OS44NyAxNy44MFExNzkuODcgMTkuMDUgMTc5LjI2IDIwLjA0UTE3OC42NSAyMS4wNCAxNzcuNTkgMjEuNjBRMTc2LjUzIDIyLjE3IDE3NS4yMCAyMi4xN0wxNzUuMjAgMjIuMTdRMTczLjg3IDIyLjE3IDE3Mi44MCAyMS42MFExNzEuNzQgMjEuMDQgMTcxLjE0IDIwLjA0UTE3MC41MyAxOS4wNSAxNzAuNTMgMTcuODBaTTE3Mi45MyAxNy44MEwxNzIuOTMgMTcuODBRMTcyLjkzIDE4LjUxIDE3My4yMyAxOS4wNVExNzMuNTMgMTkuNjAgMTc0LjA1IDE5LjkwUTE3NC41NiAyMC4yMCAxNzUuMjAgMjAuMjBMMTc1LjIwIDIwLjIwUTE3NS44MyAyMC4yMCAxNzYuMzUgMTkuOTBRMTc2Ljg3IDE5LjYwIDE3Ny4xNiAxOS4wNVExNzcuNDYgMTguNTEgMTc3LjQ2IDE3LjgwTDE3Ny40NiAxNy44MFExNzcuNDYgMTcuMDkgMTc3LjE2IDE2LjU0UTE3Ni44NyAxNiAxNzYuMzUgMTUuNzBRMTc1LjgzIDE1LjQwIDE3NS4yMCAxNS40MEwxNzUuMjAgMTUuNDBRMTc0LjU2IDE1LjQwIDE3NC4wNCAxNS43MFExNzMuNTMgMTYgMTczLjIzIDE2LjU0UTE3Mi45MyAxNy4wOSAxNzIuOTMgMTcuODBaTTE4My41MiAyMC45M0wxODMuNTIgMjAuOTNMMTg0LjgxIDE5LjQwUTE4NS40OCAyMC4yNyAxODYuMjUgMjAuMjdMMTg2LjI1IDIwLjI3UTE4Ni4yNiAyMC4yNyAxODYuMjYgMjAuMjdMMTg2LjI2IDIwLjI3UTE4Ni43OCAyMC4yNyAxODcuMDUgMTkuOTZRMTg3LjMyIDE5LjY1IDE4Ny4zMiAxOS4wNUwxODcuMzIgMTkuMDVMMTg3LjMyIDE1LjQ0TDE4NC40MiAxNS40NEwxODQuNDIgMTMuNjBMMTg5LjY3IDEzLjYwTDE4OS42NyAxOC45MVExODkuNjcgMjAuNTQgMTg4Ljg1IDIxLjM2UTE4OC4wMyAyMi4xNyAxODYuNDMgMjIuMTdMMTg2LjQzIDIyLjE3UTE4NS41MSAyMi4xNyAxODQuNzUgMjEuODVRMTg0LjAwIDIxLjUzIDE4My41MiAyMC45M1pNMjAxLjUwIDIyTDE5NC43NiAyMkwxOTQuNzYgMTMuNjBMMjAxLjM1IDEzLjYwTDIwMS4zNSAxNS40NEwxOTcuMTIgMTUuNDRMMTk3LjEyIDE2Ljg1TDIwMC44NSAxNi44NUwyMDAuODUgMTguNjNMMTk3LjEyIDE4LjYzTDE5Ny4xMiAyMC4xN0wyMDEuNTAgMjAuMTdMMjAxLjUwIDIyWk0yMDUuODggMTcuODBMMjA1Ljg4IDE3LjgwUTIwNS44OCAxNi41NCAyMDYuNDggMTUuNTRRMjA3LjA4IDE0LjU1IDIwOC4xMyAxMy45OVEyMDkuMTggMTMuNDMgMjEwLjUwIDEzLjQzTDIxMC41MCAxMy40M1EyMTEuNjUgMTMuNDMgMjEyLjU4IDEzLjg0UTIxMy41MCAxNC4yNSAyMTQuMTEgMTUuMDJMMjE0LjExIDE1LjAyTDIxMi42MCAxNi4zOVEyMTEuNzkgMTUuNDAgMjEwLjYyIDE1LjQwTDIxMC42MiAxNS40MFEyMDkuOTQgMTUuNDAgMjA5LjQwIDE1LjcwUTIwOC44NyAxNiAyMDguNTcgMTYuNTRRMjA4LjI4IDE3LjA5IDIwOC4yOCAxNy44MEwyMDguMjggMTcuODBRMjA4LjI4IDE4LjUxIDIwOC41NyAxOS4wNVEyMDguODcgMTkuNjAgMjA5LjQwIDE5LjkwUTIwOS45NCAyMC4yMCAyMTAuNjIgMjAuMjBMMjEwLjYyIDIwLjIwUTIxMS43OSAyMC4yMCAyMTIuNjAgMTkuMjJMMjEyLjYwIDE5LjIyTDIxNC4xMSAyMC41OFEyMTMuNTAgMjEuMzUgMjEyLjU4IDIxLjc2UTIxMS42NSAyMi4xNyAyMTAuNTAgMjIuMTdMMjEwLjUwIDIyLjE3UTIwOS4xOCAyMi4xNyAyMDguMTMgMjEuNjFRMjA3LjA4IDIxLjA1IDIwNi40OCAyMC4wNVEyMDUuODggMTkuMDYgMjA1Ljg4IDE3LjgwWk0yMjAuNDQgMTUuNDhMMjE3Ljg2IDE1LjQ4TDIxNy44NiAxMy42MEwyMjUuMzggMTMuNjBMMjI1LjM4IDE1LjQ4TDIyMi44MSAxNS40OEwyMjIuODEgMjJMMjIwLjQ0IDIyTDIyMC40NCAxNS40OFoiIGZpbGw9IiMxODE3MTciIHg9IjE0NS4wNzk5OTk5OTk5OTk5OCIvPjwvc3ZnPg==)](https://forthebadge.com)

[![forthebadge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMzcuMTg5OTk5OTk5OTk5OTciIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAyMzcuMTg5OTk5OTk5OTk5OTcgMzUiPjxyZWN0IGNsYXNzPSJzdmdfX3JlY3QiIHg9IjAiIHk9IjAiIHdpZHRoPSIxMzQuMDc5OTk5OTk5OTk5OTgiIGhlaWdodD0iMzUiIGZpbGw9IiMyRTI5MjkiLz48cmVjdCBjbGFzcz0ic3ZnX19yZWN0IiB4PSIxMzIuMDc5OTk5OTk5OTk5OTgiIHk9IjAiIHdpZHRoPSIxMDUuMTA5OTk5OTk5OTk5OTkiIGhlaWdodD0iMzUiIGZpbGw9IiNGNUY1RjUiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTYuMjUgMTQuNjZMMTMuNjEgMTQuNjZMMTMuNjEgMTMuNDdMMjAuMzggMTMuNDdMMjAuMzggMTQuNjZMMTcuNzIgMTQuNjZMMTcuNzIgMjJMMTYuMjUgMjJMMTYuMjUgMTQuNjZaTTI1LjYyIDIyTDI0LjE0IDIyTDI0LjE0IDEzLjQ3TDI1LjYyIDEzLjQ3TDI1LjYyIDE3LjAyTDI5LjQzIDE3LjAyTDI5LjQzIDEzLjQ3TDMwLjkxIDEzLjQ3TDMwLjkxIDIyTDI5LjQzIDIyTDI5LjQzIDE4LjIxTDI1LjYyIDE4LjIxTDI1LjYyIDIyWk00MS4yMyAyMkwzNS42NSAyMkwzNS42NSAxMy40N0w0MS4xOSAxMy40N0w0MS4xOSAxNC42NkwzNy4xMyAxNC42NkwzNy4xMyAxNy4wMkw0MC42NCAxNy4wMkw0MC42NCAxOC4xOUwzNy4xMyAxOC4xOUwzNy4xMyAyMC44Mkw0MS4yMyAyMC44Mkw0MS4yMyAyMlpNNTIuODggMjJMNTEuNDAgMjJMNTEuNDAgMTMuNDdMNTIuODggMTMuNDdMNTIuODggMTcuMDJMNTYuNzAgMTcuMDJMNTYuNzAgMTMuNDdMNTguMTcgMTMuNDdMNTguMTcgMjJMNTYuNzAgMjJMNTYuNzAgMTguMjFMNTIuODggMTguMjFMNTIuODggMjJaTTYzLjY5IDIyTDYyLjE1IDIyTDY1LjM4IDEzLjQ3TDY2LjcxIDEzLjQ3TDY5LjkzIDIyTDY4LjM5IDIyTDY3LjY5IDIwLjAxTDY0LjM5IDIwLjAxTDYzLjY5IDIyWk02Ni4wNCAxNS4yOEw2NC44MCAxOC44Mkw2Ny4yNyAxOC44Mkw2Ni4wNCAxNS4yOFpNNzMuNjIgMTguMTlMNzMuNjIgMTguMTlMNzMuNjIgMTcuMzlRNzMuNjIgMTYuMTkgNzQuMDUgMTUuMjdRNzQuNDcgMTQuMzUgNzUuMjcgMTMuODVRNzYuMDcgMTMuMzUgNzcuMTIgMTMuMzVMNzcuMTIgMTMuMzVRNzguNTQgMTMuMzUgNzkuNDAgMTQuMTJRODAuMjYgMTQuODkgODAuNDAgMTYuMjlMODAuNDAgMTYuMjlMNzguOTIgMTYuMjlRNzguODIgMTUuMzcgNzguMzkgMTQuOTZRNzcuOTYgMTQuNTUgNzcuMTIgMTQuNTVMNzcuMTIgMTQuNTVRNzYuMTYgMTQuNTUgNzUuNjQgMTUuMjZRNzUuMTIgMTUuOTYgNzUuMTEgMTcuMzNMNzUuMTEgMTcuMzNMNzUuMTEgMTguMDlRNzUuMTEgMTkuNDcgNzUuNjAgMjAuMjBRNzYuMTAgMjAuOTIgNzcuMDUgMjAuOTJMNzcuMDUgMjAuOTJRNzcuOTMgMjAuOTIgNzguMzcgMjAuNTNRNzguODEgMjAuMTQgNzguOTIgMTkuMjJMNzguOTIgMTkuMjJMODAuNDAgMTkuMjJRODAuMjcgMjAuNTkgNzkuMzkgMjEuMzVRNzguNTEgMjIuMTIgNzcuMDUgMjIuMTJMNzcuMDUgMjIuMTJRNzYuMDMgMjIuMTIgNzUuMjYgMjEuNjNRNzQuNDggMjEuMTUgNzQuMDYgMjAuMjZRNzMuNjQgMTkuMzcgNzMuNjIgMTguMTlaTTg2LjE5IDIyTDg0LjcxIDIyTDg0LjcxIDEzLjQ3TDg2LjE5IDEzLjQ3TDg2LjE5IDE3LjQ3TDg3LjAxIDE2LjQ2TDg5LjUxIDEzLjQ3TDkxLjMwIDEzLjQ3TDg4LjEzIDE3LjI1TDkxLjQ4IDIyTDg5LjczIDIyTDg3LjE2IDE4LjMxTDg2LjE5IDE5LjM0TDg2LjE5IDIyWk05Ni44MyAyMkw5NS4zNSAyMkw5NS4zNSAxMy40N0w5Ni44MyAxMy40N0w5Ni44MyAyMlpNMTAzLjEyIDIyTDEwMS42NCAyMkwxMDEuNjQgMTMuNDdMMTAzLjEyIDEzLjQ3TDEwNi45NCAxOS41NEwxMDYuOTQgMTMuNDdMMTA4LjQxIDEzLjQ3TDEwOC40MSAyMkwxMDYuOTIgMjJMMTAzLjEyIDE1Ljk1TDEwMy4xMiAyMlpNMTEyLjkwIDE4LjEzTDExMi45MCAxOC4xM0wxMTIuOTAgMTcuNDZRMTEyLjkwIDE1LjUzIDExMy44MyAxNC40NFExMTQuNzUgMTMuMzUgMTE2LjQxIDEzLjM1TDExNi40MSAxMy4zNVExMTcuODMgMTMuMzUgMTE4LjY3IDE0LjA1UTExOS41MSAxNC43NiAxMTkuNjggMTYuMDhMMTE5LjY4IDE2LjA4TDExOC4yMyAxNi4wOFExMTcuOTggMTQuNTQgMTE2LjQ0IDE0LjU0TDExNi40NCAxNC41NFExMTUuNDQgMTQuNTQgMTE0LjkzIDE1LjI2UTExNC40MSAxNS45OCAxMTQuMzkgMTcuMzdMMTE0LjM5IDE3LjM3TDExNC4zOSAxOC4wMlExMTQuMzkgMTkuNDAgMTE0Ljk3IDIwLjE3UTExNS41NiAyMC45MyAxMTYuNTkgMjAuOTNMMTE2LjU5IDIwLjkzUTExNy43MyAyMC45MyAxMTguMjEgMjAuNDJMMTE4LjIxIDIwLjQyTDExOC4yMSAxOC43NUwxMTYuNDUgMTguNzVMMTE2LjQ1IDE3LjYyTDExOS42OSAxNy42MkwxMTkuNjkgMjAuODlRMTE5LjIyIDIxLjUwIDExOC40MCAyMS44MVExMTcuNTggMjIuMTIgMTE2LjU0IDIyLjEyTDExNi41NCAyMi4xMlExMTUuNDcgMjIuMTIgMTE0LjY0IDIxLjYzUTExMy44MSAyMS4xNCAxMTMuMzcgMjAuMjRRMTEyLjkyIDE5LjMzIDExMi45MCAxOC4xM1oiIGZpbGw9IiNGNUY1RjUiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTQ4LjY1IDIyTDE0Ni4yNyAyMkwxNDYuMjcgMTMuNjBMMTUwLjExIDEzLjYwUTE1MS4yNSAxMy42MCAxNTIuMDkgMTMuOThRMTUyLjkzIDE0LjM1IDE1My4zOSAxNS4wNlExNTMuODQgMTUuNzYgMTUzLjg0IDE2LjcxTDE1My44NCAxNi43MVExNTMuODQgMTcuNjYgMTUzLjM5IDE4LjM1UTE1Mi45MyAxOS4wNSAxNTIuMDkgMTkuNDJRMTUxLjI1IDE5LjgwIDE1MC4xMSAxOS44MEwxNTAuMTEgMTkuODBMMTQ4LjY1IDE5LjgwTDE0OC42NSAyMlpNMTQ4LjY1IDE1LjQ3TDE0OC42NSAxNy45M0wxNDkuOTcgMTcuOTNRMTUwLjcwIDE3LjkzIDE1MS4wNyAxNy42MVExNTEuNDQgMTcuMjkgMTUxLjQ0IDE2LjcxTDE1MS40NCAxNi43MVExNTEuNDQgMTYuMTIgMTUxLjA3IDE1LjgwUTE1MC43MCAxNS40NyAxNDkuOTcgMTUuNDdMMTQ5Ljk3IDE1LjQ3TDE0OC42NSAxNS40N1pNMTYwLjk3IDIyTDE1OC42MCAyMkwxNTguNjAgMTMuNjBMMTYyLjQ0IDEzLjYwUTE2My41OCAxMy42MCAxNjQuNDIgMTMuOThRMTY1LjI2IDE0LjM1IDE2NS43MiAxNS4wNlExNjYuMTcgMTUuNzYgMTY2LjE3IDE2LjcxTDE2Ni4xNyAxNi43MVExNjYuMTcgMTcuNjIgMTY1Ljc0IDE4LjMwUTE2NS4zMiAxOC45OCAxNjQuNTMgMTkuMzZMMTY0LjUzIDE5LjM2TDE2Ni4zNCAyMkwxNjMuNzkgMjJMMTYyLjI3IDE5Ljc3TDE2MC45NyAxOS43N0wxNjAuOTcgMjJaTTE2MC45NyAxNS40N0wxNjAuOTcgMTcuOTNMMTYyLjI5IDE3LjkzUTE2My4wMyAxNy45MyAxNjMuNDAgMTcuNjFRMTYzLjc3IDE3LjI5IDE2My43NyAxNi43MUwxNjMuNzcgMTYuNzFRMTYzLjc3IDE2LjEyIDE2My40MCAxNS43OVExNjMuMDMgMTUuNDcgMTYyLjI5IDE1LjQ3TDE2Mi4yOSAxNS40N0wxNjAuOTcgMTUuNDdaTTE3MC41MyAxNy44MEwxNzAuNTMgMTcuODBRMTcwLjUzIDE2LjU1IDE3MS4xNCAxNS41NVExNzEuNzQgMTQuNTYgMTcyLjgwIDE0LjAwUTE3My44NyAxMy40MyAxNzUuMjAgMTMuNDNMMTc1LjIwIDEzLjQzUTE3Ni41MyAxMy40MyAxNzcuNTkgMTQuMDBRMTc4LjY1IDE0LjU2IDE3OS4yNiAxNS41NVExNzkuODcgMTYuNTUgMTc5Ljg3IDE3LjgwTDE3OS44NyAxNy44MFExNzkuODcgMTkuMDUgMTc5LjI2IDIwLjA0UTE3OC42NSAyMS4wNCAxNzcuNTkgMjEuNjBRMTc2LjUzIDIyLjE3IDE3NS4yMCAyMi4xN0wxNzUuMjAgMjIuMTdRMTczLjg3IDIyLjE3IDE3Mi44MCAyMS42MFExNzEuNzQgMjEuMDQgMTcxLjE0IDIwLjA0UTE3MC41MyAxOS4wNSAxNzAuNTMgMTcuODBaTTE3Mi45MyAxNy44MEwxNzIuOTMgMTcuODBRMTcyLjkzIDE4LjUxIDE3My4yMyAxOS4wNVExNzMuNTMgMTkuNjAgMTc0LjA1IDE5LjkwUTE3NC41NiAyMC4yMCAxNzUuMjAgMjAuMjBMMTc1LjIwIDIwLjIwUTE3NS44MyAyMC4yMCAxNzYuMzUgMTkuOTBRMTc2Ljg3IDE5LjYwIDE3Ny4xNiAxOS4wNVExNzcuNDYgMTguNTEgMTc3LjQ2IDE3LjgwTDE3Ny40NiAxNy44MFExNzcuNDYgMTcuMDkgMTc3LjE2IDE2LjU0UTE3Ni44NyAxNiAxNzYuMzUgMTUuNzBRMTc1LjgzIDE1LjQwIDE3NS4yMCAxNS40MEwxNzUuMjAgMTUuNDBRMTc0LjU2IDE1LjQwIDE3NC4wNCAxNS43MFExNzMuNTMgMTYgMTczLjIzIDE2LjU0UTE3Mi45MyAxNy4wOSAxNzIuOTMgMTcuODBaTTE4My41MiAyMC45M0wxODMuNTIgMjAuOTNMMTg0LjgxIDE5LjQwUTE4NS40OCAyMC4yNyAxODYuMjUgMjAuMjdMMTg2LjI1IDIwLjI3UTE4Ni4yNiAyMC4yNyAxODYuMjYgMjAuMjdMMTg2LjI2IDIwLjI3UTE4Ni43OCAyMC4yNyAxODcuMDUgMTkuOTZRMTg3LjMyIDE5LjY1IDE4Ny4zMiAxOS4wNUwxODcuMzIgMTkuMDVMMTg3LjMyIDE1LjQ0TDE4NC40MiAxNS40NEwxODQuNDIgMTMuNjBMMTg5LjY3IDEzLjYwTDE4OS42NyAxOC45MVExODkuNjcgMjAuNTQgMTg4Ljg1IDIxLjM2UTE4OC4wMyAyMi4xNyAxODYuNDMgMjIuMTdMMTg2LjQzIDIyLjE3UTE4NS41MSAyMi4xNyAxODQuNzUgMjEuODVRMTg0LjAwIDIxLjUzIDE4My41MiAyMC45M1pNMjAxLjUwIDIyTDE5NC43NiAyMkwxOTQuNzYgMTMuNjBMMjAxLjM1IDEzLjYwTDIwMS4zNSAxNS40NEwxOTcuMTIgMTUuNDRMMTk3LjEyIDE2Ljg1TDIwMC44NSAxNi44NUwyMDAuODUgMTguNjNMMTk3LjEyIDE4LjYzTDE5Ny4xMiAyMC4xN0wyMDEuNTAgMjAuMTdMMjAxLjUwIDIyWk0yMDUuODggMTcuODBMMjA1Ljg4IDE3LjgwUTIwNS44OCAxNi41NCAyMDYuNDggMTUuNTRRMjA3LjA4IDE0LjU1IDIwOC4xMyAxMy45OVEyMDkuMTggMTMuNDMgMjEwLjUwIDEzLjQzTDIxMC41MCAxMy40M1EyMTEuNjUgMTMuNDMgMjEyLjU4IDEzLjg0UTIxMy41MCAxNC4yNSAyMTQuMTEgMTUuMDJMMjE0LjExIDE1LjAyTDIxMi42MCAxNi4zOVEyMTEuNzkgMTUuNDAgMjEwLjYyIDE1LjQwTDIxMC42MiAxNS40MFEyMDkuOTQgMTUuNDAgMjA5LjQwIDE1LjcwUTIwOC44NyAxNiAyMDguNTcgMTYuNTRRMjA4LjI4IDE3LjA5IDIwOC4yOCAxNy44MEwyMDguMjggMTcuODBRMjA4LjI4IDE4LjUxIDIwOC41NyAxOS4wNVEyMDguODcgMTkuNjAgMjA5LjQwIDE5LjkwUTIwOS45NCAyMC4yMCAyMTAuNjIgMjAuMjBMMjEwLjYyIDIwLjIwUTIxMS43OSAyMC4yMCAyMTIuNjAgMTkuMjJMMjEyLjYwIDE5LjIyTDIxNC4xMSAyMC41OFEyMTMuNTAgMjEuMzUgMjEyLjU4IDIxLjc2UTIxMS42NSAyMi4xNyAyMTAuNTAgMjIuMTdMMjEwLjUwIDIyLjE3UTIwOS4xOCAyMi4xNyAyMDguMTMgMjEuNjFRMjA3LjA4IDIxLjA1IDIwNi40OCAyMC4wNVEyMDUuODggMTkuMDYgMjA1Ljg4IDE3LjgwWk0yMjAuNDQgMTUuNDhMMjE3Ljg2IDE1LjQ4TDIxNy44NiAxMy42MEwyMjUuMzggMTMuNjBMMjI1LjM4IDE1LjQ4TDIyMi44MSAxNS40OEwyMjIuODEgMjJMMjIwLjQ0IDIyTDIyMC40NCAxNS40OFoiIGZpbGw9IiMyRTI5MjkiIHg9IjE0NS4wNzk5OTk5OTk5OTk5OCIvPjwvc3ZnPg==)](https://forthebadge.com)

[![THP Badge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMzcuMTg5OTk5OTk5OTk5OTciIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAyMzcuMTg5OTk5OTk5OTk5OTcgMzUiPjxyZWN0IGNsYXNzPSJzdmdfX3JlY3QiIHg9IjAiIHk9IjAiIHdpZHRoPSIxMzQuMDc5OTk5OTk5OTk5OTgiIGhlaWdodD0iMzUiIGZpbGw9IiNFQ0VDRUMiLz48cmVjdCBjbGFzcz0ic3ZnX19yZWN0IiB4PSIxMzIuMDc5OTk5OTk5OTk5OTgiIHk9IjAiIHdpZHRoPSIxMDUuMTA5OTk5OTk5OTk5OTkiIGhlaWdodD0iMzUiIGZpbGw9IiMwMjAyMDIiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTYuMjUgMTQuNjZMMTMuNjEgMTQuNjZMMTMuNjEgMTMuNDdMMjAuMzggMTMuNDdMMjAuMzggMTQuNjZMMTcuNzIgMTQuNjZMMTcuNzIgMjJMMTYuMjUgMjJMMTYuMjUgMTQuNjZaTTI1LjYyIDIyTDI0LjE0IDIyTDI0LjE0IDEzLjQ3TDI1LjYyIDEzLjQ3TDI1LjYyIDE3LjAyTDI5LjQzIDE3LjAyTDI5LjQzIDEzLjQ3TDMwLjkxIDEzLjQ3TDMwLjkxIDIyTDI5LjQzIDIyTDI5LjQzIDE4LjIxTDI1LjYyIDE4LjIxTDI1LjYyIDIyWk00MS4yMyAyMkwzNS42NSAyMkwzNS42NSAxMy40N0w0MS4xOSAxMy40N0w0MS4xOSAxNC42NkwzNy4xMyAxNC42NkwzNy4xMyAxNy4wMkw0MC42NCAxNy4wMkw0MC42NCAxOC4xOUwzNy4xMyAxOC4xOUwzNy4xMyAyMC44Mkw0MS4yMyAyMC44Mkw0MS4yMyAyMlpNNTIuODggMjJMNTEuNDAgMjJMNTEuNDAgMTMuNDdMNTIuODggMTMuNDdMNTIuODggMTcuMDJMNTYuNzAgMTcuMDJMNTYuNzAgMTMuNDdMNTguMTcgMTMuNDdMNTguMTcgMjJMNTYuNzAgMjJMNTYuNzAgMTguMjFMNTIuODggMTguMjFMNTIuODggMjJaTTYzLjY5IDIyTDYyLjE1IDIyTDY1LjM4IDEzLjQ3TDY2LjcxIDEzLjQ3TDY5LjkzIDIyTDY4LjM5IDIyTDY3LjY5IDIwLjAxTDY0LjM5IDIwLjAxTDYzLjY5IDIyWk02Ni4wNCAxNS4yOEw2NC44MCAxOC44Mkw2Ny4yNyAxOC44Mkw2Ni4wNCAxNS4yOFpNNzMuNjIgMTguMTlMNzMuNjIgMTguMTlMNzMuNjIgMTcuMzlRNzMuNjIgMTYuMTkgNzQuMDUgMTUuMjdRNzQuNDcgMTQuMzUgNzUuMjcgMTMuODVRNzYuMDcgMTMuMzUgNzcuMTIgMTMuMzVMNzcuMTIgMTMuMzVRNzguNTQgMTMuMzUgNzkuNDAgMTQuMTJRODAuMjYgMTQuODkgODAuNDAgMTYuMjlMODAuNDAgMTYuMjlMNzguOTIgMTYuMjlRNzguODIgMTUuMzcgNzguMzkgMTQuOTZRNzcuOTYgMTQuNTUgNzcuMTIgMTQuNTVMNzcuMTIgMTQuNTVRNzYuMTYgMTQuNTUgNzUuNjQgMTUuMjZRNzUuMTIgMTUuOTYgNzUuMTEgMTcuMzNMNzUuMTEgMTcuMzNMNzUuMTEgMTguMDlRNzUuMTEgMTkuNDcgNzUuNjAgMjAuMjBRNzYuMTAgMjAuOTIgNzcuMDUgMjAuOTJMNzcuMDUgMjAuOTJRNzcuOTMgMjAuOTIgNzguMzcgMjAuNTNRNzguODEgMjAuMTQgNzguOTIgMTkuMjJMNzguOTIgMTkuMjJMODAuNDAgMTkuMjJRODAuMjcgMjAuNTkgNzkuMzkgMjEuMzVRNzguNTEgMjIuMTIgNzcuMDUgMjIuMTJMNzcuMDUgMjIuMTJRNzYuMDMgMjIuMTIgNzUuMjYgMjEuNjNRNzQuNDggMjEuMTUgNzQuMDYgMjAuMjZRNzMuNjQgMTkuMzcgNzMuNjIgMTguMTlaTTg2LjE5IDIyTDg0LjcxIDIyTDg0LjcxIDEzLjQ3TDg2LjE5IDEzLjQ3TDg2LjE5IDE3LjQ3TDg3LjAxIDE2LjQ2TDg5LjUxIDEzLjQ3TDkxLjMwIDEzLjQ3TDg4LjEzIDE3LjI1TDkxLjQ4IDIyTDg5LjczIDIyTDg3LjE2IDE4LjMxTDg2LjE5IDE5LjM0TDg2LjE5IDIyWk05Ni44MyAyMkw5NS4zNSAyMkw5NS4zNSAxMy40N0w5Ni44MyAxMy40N0w5Ni44MyAyMlpNMTAzLjEyIDIyTDEwMS42NCAyMkwxMDEuNjQgMTMuNDdMMTAzLjEyIDEzLjQ3TDEwNi45NCAxOS41NEwxMDYuOTQgMTMuNDdMMTA4LjQxIDEzLjQ3TDEwOC40MSAyMkwxMDYuOTIgMjJMMTAzLjEyIDE1Ljk1TDEwMy4xMiAyMlpNMTEyLjkwIDE4LjEzTDExMi45MCAxOC4xM0wxMTIuOTAgMTcuNDZRMTEyLjkwIDE1LjUzIDExMy44MyAxNC40NFExMTQuNzUgMTMuMzUgMTE2LjQxIDEzLjM1TDExNi40MSAxMy4zNVExMTcuODMgMTMuMzUgMTE4LjY3IDE0LjA1UTExOS41MSAxNC43NiAxMTkuNjggMTYuMDhMMTE5LjY4IDE2LjA4TDExOC4yMyAxNi4wOFExMTcuOTggMTQuNTQgMTE2LjQ0IDE0LjU0TDExNi40NCAxNC41NFExMTUuNDQgMTQuNTQgMTE0LjkzIDE1LjI2UTExNC40MSAxNS45OCAxMTQuMzkgMTcuMzdMMTE0LjM5IDE3LjM3TDExNC4zOSAxOC4wMlExMTQuMzkgMTkuNDAgMTE0Ljk3IDIwLjE3UTExNS41NiAyMC45MyAxMTYuNTkgMjAuOTNMMTE2LjU5IDIwLjkzUTExNy43MyAyMC45MyAxMTguMjEgMjAuNDJMMTE4LjIxIDIwLjQyTDExOC4yMSAxOC43NUwxMTYuNDUgMTguNzVMMTE2LjQ1IDE3LjYyTDExOS42OSAxNy42MkwxMTkuNjkgMjAuODlRMTE5LjIyIDIxLjUwIDExOC40MCAyMS44MVExMTcuNTggMjIuMTIgMTE2LjU0IDIyLjEyTDExNi41NCAyMi4xMlExMTUuNDcgMjIuMTIgMTE0LjY0IDIxLjYzUTExMy44MSAyMS4xNCAxMTMuMzcgMjAuMjRRMTEyLjkyIDE5LjMzIDExMi45MCAxOC4xM1oiIGZpbGw9IiMzOTMzMzMiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTQ4LjY1IDIyTDE0Ni4yNyAyMkwxNDYuMjcgMTMuNjBMMTUwLjExIDEzLjYwUTE1MS4yNSAxMy42MCAxNTIuMDkgMTMuOThRMTUyLjkzIDE0LjM1IDE1My4zOSAxNS4wNlExNTMuODQgMTUuNzYgMTUzLjg0IDE2LjcxTDE1My44NCAxNi43MVExNTMuODQgMTcuNjYgMTUzLjM5IDE4LjM1UTE1Mi45MyAxOS4wNSAxNTIuMDkgMTkuNDJRMTUxLjI1IDE5LjgwIDE1MC4xMSAxOS44MEwxNTAuMTEgMTkuODBMMTQ4LjY1IDE5LjgwTDE0OC42NSAyMlpNMTQ4LjY1IDE1LjQ3TDE0OC42NSAxNy45M0wxNDkuOTcgMTcuOTNRMTUwLjcwIDE3LjkzIDE1MS4wNyAxNy42MVExNTEuNDQgMTcuMjkgMTUxLjQ0IDE2LjcxTDE1MS40NCAxNi43MVExNTEuNDQgMTYuMTIgMTUxLjA3IDE1LjgwUTE1MC43MCAxNS40NyAxNDkuOTcgMTUuNDdMMTQ5Ljk3IDE1LjQ3TDE0OC42NSAxNS40N1pNMTYwLjk3IDIyTDE1OC42MCAyMkwxNTguNjAgMTMuNjBMMTYyLjQ0IDEzLjYwUTE2My41OCAxMy42MCAxNjQuNDIgMTMuOThRMTY1LjI2IDE0LjM1IDE2NS43MiAxNS4wNlExNjYuMTcgMTUuNzYgMTY2LjE3IDE2LjcxTDE2Ni4xNyAxNi43MVExNjYuMTcgMTcuNjIgMTY1Ljc0IDE4LjMwUTE2NS4zMiAxOC45OCAxNjQuNTMgMTkuMzZMMTY0LjUzIDE5LjM2TDE2Ni4zNCAyMkwxNjMuNzkgMjJMMTYyLjI3IDE5Ljc3TDE2MC45NyAxOS43N0wxNjAuOTcgMjJaTTE2MC45NyAxNS40N0wxNjAuOTcgMTcuOTNMMTYyLjI5IDE3LjkzUTE2My4wMyAxNy45MyAxNjMuNDAgMTcuNjFRMTYzLjc3IDE3LjI5IDE2My43NyAxNi43MUwxNjMuNzcgMTYuNzFRMTYzLjc3IDE2LjEyIDE2My40MCAxNS43OVExNjMuMDMgMTUuNDcgMTYyLjI5IDE1LjQ3TDE2Mi4yOSAxNS40N0wxNjAuOTcgMTUuNDdaTTE3MC41MyAxNy44MEwxNzAuNTMgMTcuODBRMTcwLjUzIDE2LjU1IDE3MS4xNCAxNS41NVExNzEuNzQgMTQuNTYgMTcyLjgwIDE0LjAwUTE3My44NyAxMy40MyAxNzUuMjAgMTMuNDNMMTc1LjIwIDEzLjQzUTE3Ni41MyAxMy40MyAxNzcuNTkgMTQuMDBRMTc4LjY1IDE0LjU2IDE3OS4yNiAxNS41NVExNzkuODcgMTYuNTUgMTc5Ljg3IDE3LjgwTDE3OS44NyAxNy44MFExNzkuODcgMTkuMDUgMTc5LjI2IDIwLjA0UTE3OC42NSAyMS4wNCAxNzcuNTkgMjEuNjBRMTc2LjUzIDIyLjE3IDE3NS4yMCAyMi4xN0wxNzUuMjAgMjIuMTdRMTczLjg3IDIyLjE3IDE3Mi44MCAyMS42MFExNzEuNzQgMjEuMDQgMTcxLjE0IDIwLjA0UTE3MC41MyAxOS4wNSAxNzAuNTMgMTcuODBaTTE3Mi45MyAxNy44MEwxNzIuOTMgMTcuODBRMTcyLjkzIDE4LjUxIDE3My4yMyAxOS4wNVExNzMuNTMgMTkuNjAgMTc0LjA1IDE5LjkwUTE3NC41NiAyMC4yMCAxNzUuMjAgMjAuMjBMMTc1LjIwIDIwLjIwUTE3NS44MyAyMC4yMCAxNzYuMzUgMTkuOTBRMTc2Ljg3IDE5LjYwIDE3Ny4xNiAxOS4wNVExNzcuNDYgMTguNTEgMTc3LjQ2IDE3LjgwTDE3Ny40NiAxNy44MFExNzcuNDYgMTcuMDkgMTc3LjE2IDE2LjU0UTE3Ni44NyAxNiAxNzYuMzUgMTUuNzBRMTc1LjgzIDE1LjQwIDE3NS4yMCAxNS40MEwxNzUuMjAgMTUuNDBRMTc0LjU2IDE1LjQwIDE3NC4wNCAxNS43MFExNzMuNTMgMTYgMTczLjIzIDE2LjU0UTE3Mi45MyAxNy4wOSAxNzIuOTMgMTcuODBaTTE4My41MiAyMC45M0wxODMuNTIgMjAuOTNMMTg0LjgxIDE5LjQwUTE4NS40OCAyMC4yNyAxODYuMjUgMjAuMjdMMTg2LjI1IDIwLjI3UTE4Ni4yNiAyMC4yNyAxODYuMjYgMjAuMjdMMTg2LjI2IDIwLjI3UTE4Ni43OCAyMC4yNyAxODcuMDUgMTkuOTZRMTg3LjMyIDE5LjY1IDE4Ny4zMiAxOS4wNUwxODcuMzIgMTkuMDVMMTg3LjMyIDE1LjQ0TDE4NC40MiAxNS40NEwxODQuNDIgMTMuNjBMMTg5LjY3IDEzLjYwTDE4OS42NyAxOC45MVExODkuNjcgMjAuNTQgMTg4Ljg1IDIxLjM2UTE4OC4wMyAyMi4xNyAxODYuNDMgMjIuMTdMMTg2LjQzIDIyLjE3UTE4NS41MSAyMi4xNyAxODQuNzUgMjEuODVRMTg0LjAwIDIxLjUzIDE4My41MiAyMC45M1pNMjAxLjUwIDIyTDE5NC43NiAyMkwxOTQuNzYgMTMuNjBMMjAxLjM1IDEzLjYwTDIwMS4zNSAxNS40NEwxOTcuMTIgMTUuNDRMMTk3LjEyIDE2Ljg1TDIwMC44NSAxNi44NUwyMDAuODUgMTguNjNMMTk3LjEyIDE4LjYzTDE5Ny4xMiAyMC4xN0wyMDEuNTAgMjAuMTdMMjAxLjUwIDIyWk0yMDUuODggMTcuODBMMjA1Ljg4IDE3LjgwUTIwNS44OCAxNi41NCAyMDYuNDggMTUuNTRRMjA3LjA4IDE0LjU1IDIwOC4xMyAxMy45OVEyMDkuMTggMTMuNDMgMjEwLjUwIDEzLjQzTDIxMC41MCAxMy40M1EyMTEuNjUgMTMuNDMgMjEyLjU4IDEzLjg0UTIxMy41MCAxNC4yNSAyMTQuMTEgMTUuMDJMMjE0LjExIDE1LjAyTDIxMi42MCAxNi4zOVEyMTEuNzkgMTUuNDAgMjEwLjYyIDE1LjQwTDIxMC42MiAxNS40MFEyMDkuOTQgMTUuNDAgMjA5LjQwIDE1LjcwUTIwOC44NyAxNiAyMDguNTcgMTYuNTRRMjA4LjI4IDE3LjA5IDIwOC4yOCAxNy44MEwyMDguMjggMTcuODBRMjA4LjI4IDE4LjUxIDIwOC41NyAxOS4wNVEyMDguODcgMTkuNjAgMjA5LjQwIDE5LjkwUTIwOS45NCAyMC4yMCAyMTAuNjIgMjAuMjBMMjEwLjYyIDIwLjIwUTIxMS43OSAyMC4yMCAyMTIuNjAgMTkuMjJMMjEyLjYwIDE5LjIyTDIxNC4xMSAyMC41OFEyMTMuNTAgMjEuMzUgMjEyLjU4IDIxLjc2UTIxMS42NSAyMi4xNyAyMTAuNTAgMjIuMTdMMjEwLjUwIDIyLjE3UTIwOS4xOCAyMi4xNyAyMDguMTMgMjEuNjFRMjA3LjA4IDIxLjA1IDIwNi40OCAyMC4wNVEyMDUuODggMTkuMDYgMjA1Ljg4IDE3LjgwWk0yMjAuNDQgMTUuNDhMMjE3Ljg2IDE1LjQ4TDIxNy44NiAxMy42MEwyMjUuMzggMTMuNjBMMjI1LjM4IDE1LjQ4TDIyMi44MSAxNS40OEwyMjIuODEgMjJMMjIwLjQ0IDIyTDIyMC40NCAxNS40OFoiIGZpbGw9IiNFN0YzRjUiIHg9IjE0NS4wNzk5OTk5OTk5OTk5OCIvPjwvc3ZnPg==)](https://www.thehackingproject.org/)
[![forthebadge](https://forthebadge.com/images/badges/made-with-ruby.svg)](https://forthebadge.com)

</div>

<br/>
<hr/>
<br/>

## Comment utiliser ce repo:
cloner ce repo et lancer chaque programme dans votre Terminal avec la commande :
```
ruby exo_01.rb
etc...
```

<br/>
<hr/>
<br/>

# LES CONSIGNES DE THP:
Pour chaque sous-partie, nous allons te demander de créer un programme, et de soit répondre à des questions, soit de le faire marcher.     
  
# 1. Bonjour monde
Créé un programme `exo_01.rb` qui affiche "Bonjour, monde !". Voici les lignes qu'il doit avoir d'affichées lorsque tu l'exécutes :

```
$ ruby exo_01.rb
Bonjour, monde !
```

# 2. Un programme qui dit bonjour
Écris un programme `exo_02.rb` qui demande le prénom de l'utilisateur, et qui salue l'utilisateur avec "Bonjour, prénom !"

# 3. Un programme qui calcule des âges
Écris un programme `exo_03.rb` qui demande son année de naissance à l'utilisateur, puis qui ressort l'âge que l'utilisateur a eu en 2017.

# 4. Un programme centenaire
Écris un programme `exo_04.rb` qui demande son année de naissance à l'utilisateur, puis qui ressort l'année où l'utilisateur aura 100 ans.

# 5. Un programme qui répète
Écris un programme `exo_05.rb` qui demande un nombre à l'utilisateur, puis qui écrit autant de fois "Salut, ça farte ?"

# 6. Un programme qui répète (bis)
Écris un programme `exo_06.rb` qui demande un nombre à un utilisateur, puis qui écrit autant de fois -1 "Bonjour toi !". Ainsi, si l'utilisateur rentre 10, le programme devra écrire 9 fois "Bonjour toi !"

# 7. Compter
Écris un programme `exo_07.rb` qui demande un nombre à l'utilisateur, puis qui compte jusqu'à ce nombre.

# 8. Compte à rebours
Écris un programme `exo_08.rb` qui demande un nombre à l'utilisateur, puis qui affiche un compte à rebours à partir de ce nombre, jusqu'à 0.

# 9. Afficher les années
Écris un programme `exo_09.rb` qui demande son année de naissance à l'utilisateur, puis qui va ressortir chaque année depuis son année de naissance jusqu'aujourd'hui.

# 10. Afficher tous les âges
Écris un programme `exo_10.rb` qui demande son année de naissance à l'utilisateur et qui va afficher chaque année depuis son année de naissance jusqu'aujourd'hui. Pour chaque année affichée, le programme devra annoncer l'âge que l'utilisateur avait cette année-là.

# 11. Virer les années
Le programme `exo_10.rb` est cool, mais on peut l'améliorer. Écris un programme `exo_11.rb` qui va demander son âge à l'utilisateur, et qui, pour chaque année depuis sa naissance, dira "Il y a X ans, tu avais Y ans".

# 12. Annoncer l'âge, option BG
Notre programme `exo_11.rb` est devenu beau gosse. Écris un programme `exo_12.rb` qui va faire la même chose, sauf que si X et Y sont égaux, il dira "Il y a n ans, tu avais la moitié de l'âge que tu as aujourd'hui".

# 13. Une liste d'email
Écris un programme `exo_13.rb` qui va créer une liste de 50 faux emails et les stocker dans une array. Voici le format que devront avoir les faux emails :

```
"jean.dupont.01@email.fr"
"jean.dupont.02@email.fr"
etc...
```

# 14. Afficher les bons emails
Prends le programme `exo_13.rb` et créé un programme exo_14.rb qui va reprendre l'array des emails créés, et n'afficher que les emails avec un nombre pair.

```
"jean.dupont.02@email.fr"
"jean.dupont.04@email.fr"
etc...
```

# 15. La pyramide
Construis un programme `exo_15.rb` qui va demander à l'utilisateur un nombre entre 1 et 25 et qui va sortir une pyramide à descendre d'autant d'étages que ce nombre. Voici un exemple :

```
Salut, bienvenue dans ma super pyramide ! Combien d'étages veux-tu ?
> 5
Voici la pyramide :
#
##
###
####
#####
```

# 16. La pyramide, dans l'autre sens
Reprends ton programme `exo_15.rb` et fais un programme `pyramide.rb` qui montera au lieu de descendre :

```
Salut, bienvenue dans ma super pyramide ! Combien d'étages veux-tu ?
> 5
Voici la pyramide :
    #
   ##
  ###
 ####
#####
```

Bien que légèrement différent dans l'énoncé, ce programme est bien plus dur que le `exo_15.rb`, donc c'est normal de devoir réfléchir à comment le faire 😎

# 17.  La pyramide, version expert
Crée un programme `exo_17.rb` qui va demander à l'utilisateur un nombre entre 1 et 25 et qui va sortir une pyramide qui monte et qui descend, comme montré ci-dessous :

```
Salut, bienvenue dans ma super pyramide ! Combien d'étages veux-tu ?
> 5
Voici la pyramide :
    #
   ###
  #####
 #######
#########
```
