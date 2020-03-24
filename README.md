# Lyra strictly private

The [Lyra Theme](https://github.com/TryGhost/Lyra) slightly modified, so non-members don't see the teasers of non-public posts on the home page.

**Warning**: The extracts of the non-public posts are not rendered on the frontend, but the backend still delivers them! Don't trust this implementation for critical content!

## Who sees what

-   Not logged in: On the home page you only see public posts. Note, that these posts are tagges `Public Post` (not `Free Post` as in the original Lyra theme)
-   Logged in as member: On the home page you see the extract of all posts (also the ones for paid members). When opening posts for paid members while not being a paid member, you only see the teaser and the action button to become a paid member.

## Instructions

1. [Download this theme](https://github.com/tillg/Lyra-strictly-private/dist/lyra-strictly-private.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file
3. Unzip the theme archive on your computer and locate the file called `routes.yaml`
4. Inside Ghost admin, go to the `Labs` settings area and scroll down until you see the `Custom Routes` section
5. Upload the `routes.yaml` from this theme

![screenshot](https://user-images.githubusercontent.com/120485/67228748-1fdd1400-f464-11e9-921f-ecbf5f412ed5.png)
