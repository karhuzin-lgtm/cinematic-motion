# cinematic-motion

A free Claude Code skill that turns a plain-language description into a motion video made in code: Remotion, React and three.js, rendered to MP4 in 9:16 and/or 16:9.

## Install

The easy way: open [blog.alekseimedia.com/en/kit-skill](https://blog.alekseimedia.com/en/kit-skill), copy the prompt and paste it into Claude Code. Claude downloads the skill, checks the files and installs it.

By hand: copy `SKILL.md` to `.claude/skills/cinematic-motion/SKILL.md` in your project. Copy `package.json` and `package-lock.json` to your project folder and run `npm ci`. You need Node.js 20 or newer.

Then ask Claude Code for a video, for example: "make a 20-second launch video for my app, vertical".

## Notes

- Remotion has its own license: free for individuals and small teams, see [remotion.dev/license](https://www.remotion.dev/license).
- Music and sound effects come only from audio files you own or are allowed to use.

Made by [@alekseitalksai](https://www.instagram.com/alekseitalksai/).
