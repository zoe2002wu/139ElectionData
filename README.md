# 139ElectionData

## Instructions for Gaining Access to this Repo

### 1. Add as Collaborator
Make sure I add you as a collaborator.

### 2. Clone the Repository
1. On the front page, press the green **Code** drop-down button and copy the HTTPs link.
2. Go to **Posit Cloud** and press **New Project** in the upper-right corner.
3. Select **New Project from GitHub Repository**.
4. Enter the copied HTTPs link.
5. While waiting, proceed to the next step.

---

## 2. Generate Personal Access Token on GitHub
1. In the upper-right corner of any page on GitHub, click your profile photo, then click **Settings**.
2. In the left sidebar, click **Developer settings**.
3. In the left sidebar, under **Personal access tokens**, click **Tokens (classic)**.
4. Select **Generate new token**, then click **Generate new token (classic)**.
5. In the **Note** field, give your token a descriptive name.
6. To give your token an expiration, select **Expiration**, then choose a default option or click **Custom** to enter a date.
7. Select the scope by clicking **repo**.
8. Click **Generate token**.
9. Copy the generated token.

---

## 3. Connect GitHub to Posit Cloud
1. Go to this link: [https://login.posit.cloud/identity/authentication](https://login.posit.cloud/identity/authentication).
2. Check that **GitHub** is enabled.

---

## 4. Git config
1. Find terminal on posit cloud and type in
git config --global user.email "you@example.com"
git config --global user.name "user_name"
Replace your email and name with your credentials

---

## 5. Push Changes from Posit Cloud
1. Go back to Posit Cloud and edit your project.
2. Press **Commit** in the top-right sub-window.
3. Check all the files you want to add.
4. Press **Commit**.
5. Press **Push**.
6. When prompted:
   - Input your GitHub username.
   - Input the Personal Access Token you copied from Step 2.
7. Success! 🎉

---

## 6. Pull Future Changes
Be sure to **pull** the latest changes in the future if you want to sync with updates.
