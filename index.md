---
layout: default
title: Bowz Bops
---

## Overview

Bowz Bops is a music-sharing application for the UH Mānoa
community. Students can create playlists, share their favorite
songs, and discover playlists for studying, working out,
partying, or going to the beach.

Users can organize songs into playlists and provide information
such as the song title, artist, year, genre, and an optional
Spotify or YouTube link. They can browse other users' playlists
and like their favorites.

Bowz Bops focuses on music shared by the campus community.
User profiles, personal playlists, and likes provide an
individual experience, while category rankings help students
discover popular playlists.

### Project Links

- [GitHub Organization](https://github.com/bowz-bops)
- [Application Repository](https://github.com/bowz-bops/bowz-bops)
- [Documentation Repository](https://github.com/bowz-bops/bowz-bops.github.io)

### Team Contract

[Read our signed Team Contract](https://docs.google.com/document/d/1ABdf0wHjsd3Jak8W_jqSBIyNmYgeHcjmLPMzYItvUhA/edit?usp=drivesdk)

Our team contract records our agreed contribution and behavior expectations,
conflict-resolution process, and each member's signature. It is publicly
accessible with read-only access.

## Deployment

The deployed application link will be added after the initial
Vercel deployment.

## User Guide

The initial release will include a landing page and mockups of
at least four additional pages. Features described below are
planned until implemented. The paper sketches document the proposed designs
for the team presentation; they do not demonstrate completed application pages.
Application webpage mockups are tracked separately on the M1 board.

### Landing Page

Introduces Bowz Bops with buttons to sign in and create an account (see Sign In Page and Create Account pages below).

**Paper mockup:**

![Hand-drawn landing page for Bowz Bops](images/mockups/landing-page-mockup.jpg)

*Paper mockup by Kenneth Hironaka.*

### Sign In Page

Provides labeled email and password fields and a Sign In button, with navigation back to the landing page. This is a visual mockup for M1; authentication behavior will follow the team's agreed milestone scope.

Selecting the link to create an account on the Sign In page will redirect users to a separate Create Account page (see Create Account Page mockup). 

**Paper mockup:**

![Hand-drawn Sign In page for Bowz Bops](images/mockups/sign-in-mockup.jpg)

*Paper mockup by Kenneth Hironaka.*

### Create Account Page

Provides labeled email, username, display name, password, and confirm password fields along with a "Create Account" button. The planned behavior is to create an account, sign the user in, and open My Profile and Playlists; this paper mockup does not implement registration.

![Hand-drawn create account page for Bowz Bops](images/mockups/create-account-mockup.jpg)

*Paper mockup by Kenneth Hironaka.*

### Discover Playlists

Allows users to browse playlists by activity or category and view popular playlists
ranked by likes within each category. Selecting a playlist title opens the separate
Playlist Details page. Signed-in users can like playlists and use **Save** to bookmark
other users' playlists. The location for displaying saved playlists is still to be
agreed by the team; saving does not transfer ownership or grant editing access.

**Paper mockup:**

![Hand-drawn Discover Playlists page grouped by category with creators, likes, and Save controls](images/mockups/discover-playlists-mockup.jpg)

*Paper mockup by Timothy Lovejoy.*

### Playlist Details

Displays one selected playlist, including its title, creator, category, cover image,
last-updated date, and songs. Song information includes title, artist, year, genre,
and an optional Spotify or YouTube link. The proposed page will also show a
playlist like count and Like control, although these are not drawn in the current
paper sketch. This is distinct from My Profile and Playlists, which lists the
signed-in user's own playlists.

**Paper mockup:**

![Hand-drawn Playlist Details page showing one playlist, creator, category, and song links](images/mockups/display-playlist-mockup.jpg)

*Paper mockup by Timothy Lovejoy.*

### Create or Edit Playlist

Allows signed-in users to create playlists and edit playlists they own. The form
includes playlist name, category, and the proposed visibility setting, plus song
title, artist, year, genre, and an optional Spotify or YouTube link. **Enter** adds a
song to the working list; the trash control removes one. **Save** stores playlist
information, while **Finish** on the creation sketch completes the creation flow.
The exact save flow and visibility options will be finalized during implementation.

Selecting **Edit** on a playlist card will open this separate **Create or Edit
Playlist** page to update that playlist and its songs. Selecting **Create
Playlist** will open the page with a blank form for a new playlist. This page
is separate from the Edit Profile dialog, which updates profile information only.

**Paper mockup:**

![Hand-drawn create playlist page for Bowz Bops](images/mockups/create-playlist-mockup.jpg)

*Paper mockup by Timothy Lovejoy.*

**Paper mockup:**

![Hand-drawn edit playlist page for Bowz Bops](images/mockups/edit-playlist-mockup.jpg)

*Paper mockup by Timothy Lovejoy.*

### My Profile and Playlists

Displays the signed-in user's profile and personal playlists. The proposed
layout includes profile information and playlist cards with categories,
song counts, likes, and View, Edit, and Share controls, plus a Create Playlist
button.

#### Edit Profile dialog

Selecting **Edit Profile** will open a small form dialog for updating the user's
name, username, bio, and optional photo URL, with Save Changes and Cancel
buttons. This planned dialog updates profile information only and does not
require a separate page.

#### Share Playlist dialog

Selecting **Share** on a playlist card will open a small dialog displaying that
playlist's link, with Copy Link and Close buttons. This planned feature does
not require a separate page.

**Paper mockup:** The image below illustrates the proposed page layout for
the presentation. It uses sample data; the controls and features shown are
planned and are not evidence of implemented functionality.

![Hand-drawn Bowz Bops Profile and My Playlists mockup showing a Digits-style navigation bar, profile information, and three playlist cards with View, Edit, and Share buttons.](images/mockups/profile-my-playlists.jpg)

*Paper mockup by Katrina Flessas.*

## Community Feedback

Community feedback has not yet been collected.

This section will describe feedback from UH Mānoa users and
changes made in response to their suggestions.

## Developer Guide

### Technology

- Next.js
- React
- Bootstrap 5
- PostgreSQL
- Prisma
- GitHub
- Vercel

### Local Installation

Setup instructions will be added after the application
repository is initialized and the team verifies the process.

The completed guide will explain:
1. Required software and versions.
2. How to clone the application repository.
3. How to install dependencies.
4. How to configure local environment variables.
5. How to create and initialize the database.
6. How to run the application locally.
7. How to run the project's checks.

### Deployment Instructions

Verified Vercel deployment instructions will be added here,
including required environment variable names and database
setup. Secret values will not be published.

## Development History

### Milestone 1

Milestone 1 establishes the foundation of Bowz Bops through initial
application setup and deployment, a landing page, and visual mockups
for sign-in, playlist discovery, playlist details, playlist creation and
editing, and user profiles and personal playlists. It also includes
project documentation, page screenshots, and verified setup instructions.
The team tracks assignments and progress on the M1 project board.

[View the M1 Project Board](https://github.com/orgs/bowz-bops/projects/1/views/2)

### Milestone 2

The second milestone's planned work will be documented here
when the team transitions to M2.

M2 Project board link: To be added.

## Contact Us

Bowz Bops is developed by three UH Mānoa students.

<div class="team-grid">
  <div class="team-card">
    <img src="https://avatars.githubusercontent.com/u/145536182?s=176&v=4" alt="Kenneth Hironaka's GitHub avatar" width="88" height="88" loading="lazy">
    <strong>Kenneth Hironaka</strong>
    <a href="https://github.com/kenneth-hironaka">@kenneth-hironaka</a>
  </div>
  <div class="team-card">
    <img src="https://avatars.githubusercontent.com/u/123511180?s=176&v=4" alt="Timothy Lovejoy's GitHub avatar" width="88" height="88" loading="lazy">
    <strong>Timothy Lovejoy</strong>
    <a href="https://github.com/LyingCakes">@LyingCakes</a>
  </div>
  <div class="team-card">
    <img src="https://avatars.githubusercontent.com/u/327657024?s=176&v=4" alt="Katrina Flessas's GitHub avatar" width="88" height="88" loading="lazy">
    <strong>Katrina Flessas</strong>
    <a href="https://github.com/katrinaflessas">@katrinaflessas</a>
  </div>
</div>

For questions or feedback, please
[open an issue](https://github.com/bowz-bops/bowz-bops/issues).

