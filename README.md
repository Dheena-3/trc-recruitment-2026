# TRC Recruitment 2026 – Submission Repository

Submission template for the **Induction – The Robotics Club (TRC) 2026** recruitment tasks.
Each domain has its own folder, and each folder has a `TASK.md` with the tasks, rules and what to submit.

| Folder | Domain | Read |
| --- | --- | --- |
| [`01-github/`](01-github/) | Git & GitHub | [TASK.md](01-github/TASK.md) |
| [`02-mobile-robotics/`](02-mobile-robotics/) | Mobile Robotics | [TASK.md](02-mobile-robotics/TASK.md) |
| [`03-electronics/`](03-electronics/) | Electronics | [TASK.md](03-electronics/TASK.md) |
| [`04-mechanical-design/`](04-mechanical-design/) | Mechanical Design | [TASK.md](04-mechanical-design/TASK.md) |

Learning material (Tinkercad, Arduino, sensors, ESP32) is in [`RESOURCES.md`](RESOURCES.md).
The official write-up of the rules is the
[TRC Recruitment Task – Submission Instructions](https://docs.google.com/document/d/1RiHDesvfT6KRwyinqOx4AFWq15RmLzpKiroPKc7YGlc/edit?usp=sharing).
If anything here disagrees with it, the official document wins.

## Which domains do I need to do?

- Pick your domain(s) as per the recruitment sheet. Only tasks marked compulsory in each `TASK.md` are required for interview selection.
- **Electronics + Mobile Robotics:** if you choose these two, Mechanical Design is not mandatory.
- **Mechanical Design + Mobile Robotics:** if you choose these two, Electronics is not mandatory.
- Interested students may attempt all domains.

## How to submit

1. **Create your own copy** of this repo. On GitHub click **Use this template → Create a new repository**
   (or **Fork**). Name it `trc-recruitment-2026-<your-name>`.
   Don't clone this repo directly: you won't have push access to it.
2. **Clone your copy** to your machine:
   ```bash
   git clone https://github.com/<your-username>/trc-recruitment-2026-<your-name>.git
   cd trc-recruitment-2026-<your-name>
   ```
3. Do the tasks and place your files in the matching folder (see each `TASK.md`).
4. Commit often with meaningful messages and push:
   ```bash
   git add .
   git commit -m "03-electronics: add level-easy circuit and code"
   git push
   ```
5. **Add your mentors as collaborators:** repo **Settings → Collaborators → Add people**,
   then enter each mentor's GitHub username.
6. Submit your repository link through the channel given in the recruitment sheet.

## Ground rules

- Keep the folder names as they are.
- Use meaningful names for inputs, outputs, variables and files.
- Avoid using AI wherever possible, especially when writing code. Your own work only; you may be asked about it in the interview.
