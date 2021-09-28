<img src="./images/NoteBlock_tm_logo_NOTEXT_white_background.jpg" align="center" />

# NOTEBLOCK
A DeMI (Decentralized Music Industry) ecosystem centered around an auctionable non-fungible token.

NoteBlock Tokenizes your music.

NoteBlock lets you license your work using blockchain.

NoteBlock includes a decentralized licensing marketplace.
NoteBlock has built-in charitable contributions to support diversity in the Music Industry.
We have decentralized decision making through governance tokens
We have revenue sharing: all fees are paid out to all governance token holders!

## Webapp Outline
Currently a simple landing page meant to inform newcomers
1. HomePage - outlines products + services + core elements to project, 
2. Auth0 Sign Up 

## Starting State
When this shared space was created, the following was already created and completed by Mark alone:
- Functioning Javascript application using React
- Application hosted on AWS Amplify at Marks expense
- noteblockmusic.com and noteblock.io Google domains that Mark integrated with AWS Amplify were rented at Marks expense
- Link to Medium blog Mark wrote on behalf of Noteblock on function application
- Logos and names created by Mark are seen on functioning application
- Product design, roadmap, products, etc

## TODO - Short Term + low errort
- [x] Authentication research **Completed by Antony**
- [x] Integrate Auth0 with a Log In/ Sign In button - works on localhost **Completed by Antony**
- [x] Setup GitHub Pro to require approvals for PRs from forked repo **Completed and Paid for by Mark**
- [ ] Upgrade components to MaterialUI to reduce complexity + to upgrade look + feel **WIP by Antony**
- [ ] Upgrade app to typescript to faster development + access to better documented libraries **WIP by Antony**
- [ ] AWS env variable setup for Auth0 with PROD account **WIP - Assigned to Mark** 
- [ ] Side Nav for documentation, white paper, etc **WIP by Anotny**

## TODO  next priorities:
- [ ] Choose 3rd party for email newsletter
- [ ] Integrate Email Newsletter Sign up
- [ ] Connect to Metamask functionality
- [ ] Functionality dependant on successful authentication (such as connecting to metmask)
- [ ] Sitemap.xml setup for SEO

## Roadmap - i.e. longer term TODOs:
- [ ] Creation of Tokens Page
  - Page will offer "create a token" button which will open an upload modal. A usser ought to be able to upload .mp3, .wav, .fl, and other music file types
  - User will see tiles that represent the tokens they already have created. Tiles will be paginated so that users with > a number, perhaps 10, will have a page 2 etc 
- [ ] Creation of Auctions page
- [ ] Creation of Licensing page
- [ ] Creation of Coin Reservation page for 50 day resevation period
- [ ] Routing for Tokens page, Auctions page, Licensing Page from tabs in the header. Mock up will be provided.
- [ ] POST and GET requests to IPFS for audio file storage
- [ ] Add google analytic code to env variables **Assigned to Mark**


# Below will be moved into a spreadsheet of some kind. The info is a placeholder

## History:

### Commit History

#### Repo: noteblockcommons/noteblock_webapp
- `4343be788497cdbc47776eb79fd712cf0fde16fe` by **Mark** on `master` branch
Init commit
- `f339ba30a048ff9596e3cafd2802da34e4bb7448` by **Antony** on `sso-auth` branch
Adding AuthProvider
- `bc91a87a5a8e1babef0d401207c6026b5db36604` by **Antony** on `sso-auth` branch
Adding Auth to existing Sign Up button
- `1f70c1df4cae0556387687445abfc7483394b8a2` by **Antony** on `sso-auth` branch
README.md update to describe changes
- `42ae855af652ff9e343154c98f57719766ea38df` by **Antony** on `sso-auth-ts` branch
Upgrades to enable typescript in app for future development


#### Repo: forked repo -> noteblockcommons/NoteBlockWebApp


### Issue history
#### Repo: noteblockcommons/noteblock_webapp
1. As a user, I want to be authenticated by the app
  - Completed on localhost by Antony
2. Convert application to typescript 
  - Completed on localhost by Antony
3. Convert app to use Material UI over current User facing module
  - WIP by Antony
4. auth0 integration also requires clientId setup
  - Reviewed by both Mark and Antony over call on 9/25/21, Solution found together, WIP by Mark
5. Create button for metamask connection by user
  - Showcased by Mark on 9/25/21 call, WIP by Antony
6. Make metamask button visible or active after login 
  - Showcased by Mark on 9/25/21 call, WIP by Antony

#### Repo: forked repo -> noteblockcommons/NoteBlockWebApp
1. Upgrade application to use typescript
  - Completed by Antony 9/26. Pending PR reviewal
2. Upgrade application to use Material-UI 
  - WIP by Antony. Suggested by Antony as well

## Technical Notes:
