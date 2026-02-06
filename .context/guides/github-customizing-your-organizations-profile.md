# Customizing your organization's profile

You can share information about your organization by customizing your organization's profile.

## About your organization's profile page

You can customize your organization's Overview page to show a README and pinned repositories dedicated to public users or members of the organization.

Members of your organization who are signed into GitHub, can select a `member` or `public` view of the README and pinned repositories when they visit your organization's profile page.

The view defaults to `member` if either a members-only README or members-only pinned repositories are present, and `public` otherwise.

Users who are not members of your organization will be shown a `public` view.

### Pinned repositories

You can give users easy access to important or frequently used repositories, by choosing up to six repositories for public users and six repositories for members of the organization. Once you pin repositories to your organization profile, the "Pinned" section is shown above the "Repositories" section of the profile page.

Only organization owners can pin repositories. For more information, see [Pinning repositories to your organization's profile](#pinning-repositories-to-your-organizations-profile).

### Organization profile READMEs

You can share information about how to engage with your organization by creating an organization profile README for both public users and members of the organization. GitHub shows your organization profile README in the "Overview" tab of your organization.

You can choose what information to include in your organization profile README. Here are some examples of information that may be helpful.

- An "About" section that describes your organization
- Guidance for getting help in the organization

You can format text and include emoji, images, and GIFs in your organization profile README by using GitHub Flavored Markdown. For more information, see [Getting started with writing and formatting on GitHub](/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github).

## Adding a public organization profile README

> [!NOTE] Public organization profiles are not available with Enterprise Managed Users.

The content of public `README.md` will appear on your organization's public profile.

1. If your organization does not already have a public `.github` repository, create a public `.github` repository.
2. In your organization's `.github` repository, create a `README.md` file in the `profile` folder.
3. Commit the changes to the `README.md` file.

## Adding a member-only organization profile README

The content of a member-only `README.md` will be displayed in the member view of your organization's profile.

1. If your organization does not already have a `.github-private` repository, create a private repository called `.github-private`.
2. In your organization's `.github-private` repository, create a `README.md` file in the `profile` folder.
3. Commit the changes to the `README.md` file.

## Pinning repositories to your organization's profile

You can pin repositories that you want to feature, such as those that are frequently used, to your organization's profile page. To choose which repositories to pin to your organization's profile, you must be an organization owner.

1. Navigate to your organization's profile page.

2. In the right sidebar of the page, select the **View as** dropdown menu, then click **Public** or **Member**.

3. Navigate to the settings for pinned repositories.
   - If you already have pinned repositories, in the "Pinned" section, click **Customize pins**.
   - If you haven't yet pinned any repositories, in the right sidebar, click **pin repositories**.

4. In the "Edit pinned repositories" dialog box, select a combination of up to six public, or private repositories to display.

5. Click **Save pins**.

## Changing your organization's profile picture

When you create an organization, GitHub provides you with a randomly generated "identicon." The identicon is generated from a hash of your organization's user ID, so there's no way to control its color or pattern.

You can replace the identicon with an image that represents your organization. To replace the image, you can upload a new image or use a Gravatar image.

### Uploading an image

1. In the upper-right corner of GitHub, click your profile picture, then click **Organizations**.
2. Next to the organization, click **Settings**.
3. Under your profile picture, click **Upload new picture**, then select an image.

### Using a Gravatar image

1. In the upper-right corner of GitHub, click your profile picture, then click **Organizations**.
2. Next to the organization, click **Settings**.
3. In the "Gravatar email (Private)" field, enter the email address associated with your Gravatar image.
4. Click **Update profile**.

## Further reading

- [About the repository README file](/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
- [Managing your profile README](/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
