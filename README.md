# Template.Docs

> “[One] who works with the door open gets all kinds of interruptions, but [they] also occasionally gets clues as to what the world is and what might be important.” — Richard Hamming

This project is a fork of the quartz project where some of the default configuration has been altered to make rolling out docs projects easier for ForgeFX.

After installing the template quartz commands should still be ran.

Open the git terminal and run:

```
npm i
npx quartz create
```

If you get errors on `npm i` or `npx quartz create` you might be missing some package installs on your computer. Install the packages until the errors are resolved, sending screenshots to ChatGPT is a simply and effective way to resolve the issues. 

If you want to test a local build run:
```
npx quartz build --serve
```

Hosting should already be setup as I've added the `quartz/.github/workflows/deploy.yml` to the github workspace already, pages just need to be enabled in the project settings and set to use github actions for deployment.
```
Head to “Settings” tab of your forked repository and in the sidebar, click “Pages”. Under “Source”, select “GitHub Actions”.
```

To customize the page general metadata you can edit the file `quartz.config.ts` in the project root, documentation for the config file can be found here: https://quartz.jzhao.xyz/configuration

To author content for the website the simplest method is to download https://obsidian.md/ and open the "content" folder of this project as a vault. You can also edit the markdown directly or use a different editor like Cursor IDE if you like. 

# Deployment
The website will automatically update with every commit made to the repo might just take a few minutes to update, you can track it's progress from the deployment tab on the github repo home page. 


Quartz 4 Documentation: https://quartz.jzhao.xyz/