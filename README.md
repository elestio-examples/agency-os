# Agency OS docker compose demo CI/CD pipeline

<a href="https://dash.elest.io/deploy?source=cicd&social=dockerCompose&url=https://github.com/elestio-examples/docker-compose-agency-os"><img src="deploy-on-elestio.png" alt="Deploy on Elest.io" width="180px" /></a>

Example CI/CD pipeline showing how to deploy a direct instance to elestio.

<img src="agency-os.png" style='width: 100%;'/>
<br/>
<br/>

# Once deployed ...

You can connect to the Agency OS Dashboard:

    Access URL: https://[CI_CD_DOMAIN]/
    Login: [ADMIN_EMAIL]
    Password: [ADMIN_PASSWORD]

# Installation Steps

Welcome to the installation guide for Agency OS! Follow the steps below to set up Agency OS on your Directus instance.

1. Open Terminal:

- Connect to your server via SSH.
- Click on the `Open terminal` button located at the top right of the screen.

2. Run Installation Command:

- Execute the following command in the terminal:

      npx directus-template-cli@latest apply

3. Answer the Questions:

- After running the command, you will be prompted with a series of questions.

      What type of template would you like to apply?

- Choose: `Official templates`

      Select a template.

- Choose: `AgencyOS`

      What is your Directus URL?

- Type: `https://[CI_CD_DOMAIN]`

      What is your Directus Admin Token?

- Type: `[ADMIN_PASSWORD]`

4. Wait for Installation:

- Allow the installation process to complete. This may take some time depending on your internet connection and server specifications.

5. Verification:

- Once the installation is complete, verify that Agency OS has been successfully installed on your Directus instance.

# Note

By default, it is preloaded with version 9.26.0, and subsequent versions will be accompanied by a BSL license. For additional information on the Directus BSL license, you can check <a href="https://directus.io/bsl">here.</a>
