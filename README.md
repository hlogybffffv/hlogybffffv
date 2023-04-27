### Hi there 👋

<!--
**hlogybffffv/hlogybffffv** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->/
Blog

Changelog
Subscribe to all Changelog posts via RSS or follow GitHub Changelog on Twitter to stay updated on everything we ship.

→ ~ cd github-changelog
→ ~/github-changelog|main git log main
showing all changes successfully
All Categories
GitHub Actions Importer Feature Flags
April 24, 2023
actionsactions-importerclifeaturega
You can now customize your GitHub Actions Importer experience using feature flags. You can use the --enable-features and --disable-features options to select specific features to enable or disable for the duration of the command.
image

See more 
GitHub Actions: Faster macOS runners are now available in open public beta!
April 24, 2023
actions
XL macOS runners can now be used by any developer, without the need to sign-up! You can try the new runners today by setting the runs-on: key to macos-latest-xl, macos-12-xl, or macos-13-xl in your workflow file. The runners are available today to all customers!

See more 
GitHub Actions: macOS 13 is now available
April 24, 2023
actions
The macOS 13 (Ventura) beta runner image is now available for GitHub-hosted macOS runners. You can try it today by setting the runs-on: key to macos-13 or macos-13-xl in your workflow file. The full list of software available for macOS 13 can be found here. If you see any issues with your workflows when using macOS 13, please create an issue in the runner-images repository.

See more 
One Click Into GitHub Codespaces
April 24, 2023
codespacesone-click
Codespaces has a number of new features to get you coding fast, from anywhere on the web, with a single click. Let's jump right in!

See more 
Enhancements for admins bypassing branch protections on github.com
April 20, 2023
branchespoliciesrepositoriesrules
When editing a file on github.com, repo admins, actors with the bypass branch protections permissions, and actors in bypass lists on branch protections will now default to creating a new branch instead for directly committing. You can still commit directly to a protected branch, but doing so will add notifications in-line highlighting that some rules will be bypassed.

See more 
Team Sync no longer invites or removes organization members by default
April 20, 2023
enterpriseghec
For GitHub Enterprise Cloud customers, team sync no longer invites members to organizations by default. For existing team sync customers we have added a configuration option to disable automatic organization provisioning for users that are synced from your identity provider groups. Team sync will not remove users from an organization when they are removed from a team.

See more 
GitHub Actions: Create and share your own deployment protection rules for safe and controlled deployments
April 20, 2023
actionsdeploymentsprotectionrules
GitHub today announced public beta support for custom deployment protection rules for safely rolling out deployments using GitHub Actions.

See more 
Pull request merge queue (public beta): API support and recent fixes
April 19, 2023
merge-queuepublicbetapull-requests
As we work towards general availability of pull request merge queue, we want to thank everyone that has provided feedback ❤ (keep it coming!) and let you know about some recent fixes and new API support.

See more 
npm provenance public beta
April 19, 2023
npmsecurity
npm packages built on a cloud CI/CD system (like GitHub Actions) can now publish with provenance, meaning the package has verifiable links back to its source code and build instructions.

See more 
Open a private vulnerability report with REST API
April 18, 2023
advisory-databasesecuritysecurity-and-compliance
You can now use the REST API to open a private vulnerability report on open-source repositories that have this feature enabled.

See more 
Fixed bug that allowed a hovercard URL to be used to display the name, description, and star count of any repository
April 17, 2023
repositoriessecurity
On March 30, 2023, we fixed a bug that allowed a dependency graph hovercard URL to be used to retrieve the name, description, and star count of any repository on GitHub.com. The bug was introduced on March 28, 2023 and our investigation has found no evidence of exploitation. To exploit the bug, a specific header needed to be set when making a request to the URL and the numeric ID of a repository provided. The URL would then return the HTML content designed to be used for a hovercard UI element with the repository name, description, and star count in the response.

See more 
Organize Discussions Categories into Sections
April 17, 2023
categoriesdiscussionsorganizesections
Since the introduction of Category Sections to organize content in our own community, users have asked for similar features to organize their own Discussions. Today, we're introducing the ability for all maintainers to group their Discussion categories into sections. We think this will help users better organize content, and also find new content more easily.
Screenshot 2023-04-17 at 8 28 12 AM

See more 
Enable security features for multiple repositories from your organization-level security coverage page
April 17, 2023
advanced-securityenterprisesecurity-and-compliance
Available in public beta today, the security coverage page now includes multi-repository enablement, which lets you enable or disable security features across several repositories at once. This feature improves upon the "enable all" feature that only allows you to enable one security feature at a time for all repositories within the organization.

See more 
Introducing Repository Rules Public Beta
April 17, 2023
branchesfeaturespoliciespull-requestsrepositoriesrules
Today we are announcing the public beta of repository rules! 🎉

See more 
Marking a threaded comment as the answer
April 17, 2023
githubdiscussionsmoderationq&a
When we introduced GitHub Discussions in 2020, we allowed users to mark an answer to a question in the "Q&A" Discussions category. As the feature began getting more usage, we noticed that often, the real answer to a question may live in a reply to an answer. Today, we are introducing the ability for users to mark a threaded reply as the answer to a question.

See more 
Deprecation: Importing non-Git repositories with GitHub Importer
April 17, 2023
migrations
GitHub Importer allows you to import repositories from other code hosting platforms to GitHub.com using a UI or REST API.

See more 
Automatic rebases on Dependabot pull requests stop after 30 days of inactivity
April 13, 2023
dependabotsecurity-and-compliance
When changes in a repository make a Dependabot pull request out-of-date, Dependabot will automatically rebase it so that it is able to be merged without your manual effort. With this release, if a PR has not been merged for 30 days, Dependabot will stop rebasing it and will include a note about this in the PR body. You will still be able to manually rebase and merge the pull request. We've heard your feedback about Dependabot noisiness and are making Dependabot quieter and more focused on repositories you care about. For enterprise customers, this improvement has the added benefit of enhanced efficiency with your self-hosted GitHub Actions runners. For Enterprise Server customers, this update will be available to you in GHES 3.10.

See more 
Repository topics and team filters for enterprise-level Dependabot, secret scanning, and code scanning pages
April 13, 2023
advanced-securitycode-scanningenterprisesecurity-and-compliance
You can now filter by repository topic or team on the enterprise-level Dependabot, code scanning, and secret scanning pages in security overview.

See more 
Dependabot now supports fetching release notes and changelogs for Docker images
April 13, 2023
dependabotsecurity-and-compliance
You can now fetch release notes, changelogs and commit history for Docker update pull requests with Dependabot. This will allow you to quickly evaluate the stability risk of the dependency upgrade. To enable support, add the org.opencontainers.image.source label to the Dockerfile with the URL of the source repository. Additionally, the repository should be tagged with the same tags as the published Docker images. This allows Dependabot to understand which repo and commit is associated each version/tag of a Docker image. Here's an example repository demonstrating this setup.

See more 
Secret scanning now detects secrets leaked historically in issues
April 12, 2023
advanced-securityenterprisesecret-scanningsecuritysecurity-and-compliance
GitHub Advanced Security customers using secret scanning can now view any secrets exposed historically in an issue's title, description, or comments within the UI or the REST API. This expanded coverage will also detect and surface secrets matching any custom pattern defined at the repository, organization, or enterprise levels.

See more 
Subscribe to The GitHub Insider
A newsletter for developers covering techniques, technical guides, and the latest product innovations coming from GitHub.

Your email address
Yes please, I’d like GitHub and affiliates to use my information for personalized communications, targeted advertising and campaign effectiveness. See the GitHub Privacy Statement for more details.

Subscribe
Product
Features
Security
Enterprise
Customer Stories
Pricing
Resources
Platform
Developer API
Partners
Atom
Electron
GitHub Desktop
Support
Docs
Community Forum
Training
Status
Contact
Company
About
Blog
Careers
Press
Shop
GitHub on Twitter
GitHub on Facebook
GitHub on YouTube
GitHub on Twitch
GitHub on TikTok
GitHub on LinkedIn
GitHub’s organization on GitHub
© 2023 GitHub, Inc.
Terms
Privacy
