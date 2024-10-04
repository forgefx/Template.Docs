
# **Template.Docs**

> **“One who works with the door open gets all kinds of interruptions, but they also occasionally get clues as to what the world is and what might be important.”**  
> — Richard Hamming

This project is a fork of the **Quartz** project, with adjustments to the default configuration to streamline the rollout of documentation projects for **ForgeFX**.

---

## **Setup Instructions**

To get started, follow these steps:

1. **Install Dependencies**:
   Open your terminal and run the following commands:
```bash
npm i
npx quartz create
```

If you encounter errors during the install or setup steps, it may indicate missing packages on your system. Install the necessary packages and continue. 

> **Pro Tip**: Sending screenshots of errors to ChatGPT is an easy and efficient way to troubleshoot issues.

2. **Local Development**:
To test the build locally, use the following command:

```bash
npx quartz build --serve
````

---

## **Deployment Instructions**

The deployment process is already set up for you. The `deploy.yml` workflow file has been added to the `.github/workflows/` directory of the project. To finalize the deployment:

1. Navigate to the **Settings** tab of your forked repository.
2. In the sidebar, click **Pages**.
3. Under **Source**, select **GitHub Actions** for deployment.

Once enabled, your website will automatically update with each commit to the repository. Please note, updates may take a few minutes to appear. You can track the progress from the **Deployments** tab on the repository’s home page.

---

## **Customization**

To customize the page's metadata, you can modify the `quartz.config.ts` file located in the project root. Detailed documentation for configuring Quartz can be found [here](https://quartz.jzhao.xyz/configuration).

### **Authoring Content**

The easiest way to create and manage content is to use [Obsidian](https://obsidian.md/). Simply open the **content** folder of this project as a vault in Obsidian. Alternatively, you can directly edit the markdown files or use another editor like **Cursor IDE**.

---

## **Additional Resources**

- **Quartz 4 Documentation**: [https://quartz.jzhao.xyz/](https://quartz.jzhao.xyz/)

---