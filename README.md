/**
    * @name Compact-Cord
    * @version 1.0.0
    * @description A material-esk theme, designed in dark mode. This theme shows off a very clean and material UI, with resizable components.
    * @author Sceptor#8372
    * @website https://github.com/Sczptor/CC-Compact-Cord/
    * @source https://github.com/Sczptor/CC-Compact-Cord/blob/main/Compact-Cord.theme.css
**/

/*
_________                                     __    _________                  .___
\_   ___ \  ____   _____ ___________    _____/  |_  \_   ___ \  ___________  __| _/
/    \  \/ /  _ \ /     \\____ \__  \ _/ ___\   __\ /    \  \/ /  _ \_  __ \/ __ | 
\     \___(  <_> )  Y Y  \  |_> > __ \\  \___|  |   \     \___(  <_> )  | \/ /_/ | 
 \______  /\____/|__|_|  /   __(____  /\___  >__|    \______  /\____/|__|  \____ | 
        \/             \/|__|       \/     \/               \/                  \/
*/

/* Variables */
:root {
  /*  Discord */
  --background-primary: #18191a;
  --background-secondary: #242526;
  --background-tertiary: #18191a;
  --background-floating: var(--background-primary);
  --userarea-background: var(--background-tertiary);
  --background-secondary-alt: #242526;
  --header-primary: #fff;
  --header-secondary: #b9bbbe;
  --background-accent: #242526;

  --text-link: #25b4ec;
  --text-normal: #dcddde;
  --text-muted: #969696;

  --text-colour: #fff;

  /* HSL */
  --server-size: var(--HSL-server-icon-size, var(--HSL-size, 35px));
  --server-spacing: var(--HSL-server-spacing, var(--HSL-spacing, 10px));
  --server-container: calc(var(--server-size) + 20px);
}

/* Colour fixes */
.peopleColumn-29fq28 {
  background-color: var(--background-primary)
}

.theme-dark .root-1gCeng {
  background-color: var(--background-secondary)
}

.members-1998pB, .members-1998pB>div {
  background-color: var(--background-primary);
  box-shadow: 0 -10px 10px rgba(0, 0, 0, 0.562)
}

.contentRegionScroller-26nc1e {
  background-color: #20202079 !important;
}

.sidebarRegionScroller-3MXcoP,.scrollerBase-289Jih,
.sidebar-CFHs9e {
  background-color: var(--background-primary);
}

.perksModalContentWrapper-2HU6uL {
  background-color: var(--background-primary);
}

/* User container in header */
.container-3baos1 {
  position: absolute;
  top: 0;
  right: 0;
  height: 48px;
  width: 220px;
  box-sizing: border-box;
}

.sidebar-2K8pFh {
  z-index: 101;
}

.container-1r6BKw {
  padding-right: 250px;
  box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.562);
}

/* Watermark */
.wordmarkWindows-1v0lYD {
  display: none;
}

/* Minimized search bar */
.search-2oPWTC:not(.open-6_Y_aH) 
.searchBar-3dMhjb { 
  width: 27px; 
  transition: 0.25s; 
  background-color: transparent;
}

.search-2oPWTC:not(.open-6_Y_aH):hover
.searchBar-3dMhjb {
  width: 240px; 
  background-color: var(--background-tertiary)}

.search-2oPWTC:not(.open-6_Y_aH) 
.iconContainer-O4O2CN { 
  transform: scale(1.3); 
  transition: 0.25s;
}

.search-2oPWTC:not(.open-6_Y_aH):hover 
.iconContainer-O4O2CN { 
  transform: scale(1);
}
.icon-3cZ1F_ { 
  color: var(--text-colour)
}

/* Right click popout */
.menu-3sdvDG {
  animation: slide-in 200ms ease;
  transform-origin: left;
}

@keyframes slide-in {
  0% {
      transform: scaleX(0);
  }
  100% {
      transform: scaleX(1);
  }
}

/* Fly in Voice Chat buttons - Tropical#4355 */
.container-3baos1 .noWrap-3jynv6 {
  width: 0px;
  opacity: 0;
  pointer-events: none;
  transition: all .25s ease-in-out;
}

.container-3baos1:hover .noWrap-3jynv6 {
  width: 100px;
  opacity: 1;
  pointer-events: all;
}

/* Channel list */

.scroller-1JbKMe, .privateChannels-1nO12o, .container-3w7J-x {background: transparent;}
.sidebar-2K8pFh {
	background: transparent;
  box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.562);
}

.header-2V-4Sw {
  box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.562);
}

/* Compact channels - Sethryl#8645*/
.wrapper-2jXpOf {
  padding: 0px;
}

.containerDefault-3tr_sE, .containerDragAfter-Zk9oyx, .containerDragBefore-1YqewQ, .containerUserOver-98-yc7 {
  padding-top: 4px;
}

.mainContent-u_9PKf {
  padding: 5px;
}

.sidebar-2K8pFh {
  width: 200px;
}

.animatedContainer-1NSq4T, .content-3YMskv [style="height: 84px;"], .bannerImage-3KhIJ6{
  display: none;
}
.hasBanner-2SrLR3 .header-2V-4Sw, .hasBanner-2SrLR3 .header-2V-4Sw:hover{
  color: var(--header-primary);
  box-shadow: var(--elevation-low);
}
.iconTierOne-s_oiRb, .iconTierTwo-1JOWNK {
  color: var(--text-muted);
}

/* Remove new rebrand font */
html:root {
  --font-display: var(--font-primary);
}

/* Changes status colours */
rect[fill^="hsl(262,"] {fill: rgb(216, 83, 216)}
rect[fill^="hsl(139,"] {fill: #65e265}
rect[fill^="hsl(38,"] {fill: #fcfc17de}
rect[fill^="hsl(359,"] {fill:#fd4744}
rect[fill^="hsl(214,"] {fill: rgba(83, 83, 83, 0.479)}

/* Title bar */
.titleBar-AC4pGV {
  background: #24252673;
  margin-top: 0;
  height: 10px;
  padding-right: 5px;
}

.winButton-iRh8-Z {
  width: 21px;
  height: 21px;
  padding-top: 2px;
}

/* Removes offline screen, replaces with a popup */
.container-16j22k {background: transparent; pointer-events: none}
.container-16j22k>div {display: none}
.container-16j22k::before {
    content: "You've gone offline";
    display: block;
    bottom: 24px; right: 24px;
    position: absolute;
    padding: 8px 16px;
    background-color: #f04747;
    border-radius: 4px;
    color: #fff;
    font-weight: 500
}

/* Horizontal server list - https://github.com/DiscordStyles/HorizontalServerList */

#app-mount .app-1q1i1E .base-3dtUhz {
  top: var(--server-container) !important;
  position: absolute !important;
  left: 0 !important;
  right: 0;
  bottom: 0;
  max-width: 100%;
}
#app-mount .sidebar-2K8pFh {
  border-radius: 0;
}
#app-mount [class*=unreadMentionsIndicator] {
  width: var(--server-size);
  padding: 0;
  left: 50%;
  transform: translateX(-50%);
  height: auto;
}
#app-mount .guilds-1SWlCJ {
  transform-origin: top left;
  transform: rotate(-90deg);
  height: 100vw !important;
  width: var(--server-container);
  top: var(--server-container);
  bottom: unset;
  position: absolute !important;
  left: 0;
}
#app-mount .guilds-1SWlCJ > [data-list-id=guildsnav] {
  margin-bottom: 0 !important;
}
#app-mount .guilds-1SWlCJ .scrollerWrap-1IAIlv {
  width: calc(100% + 30px);
}
#app-mount .guilds-1SWlCJ .scrollerBase-289Jih {
  padding-top: 0 !important;
  background: #18191a !important;

  box-shadow: 0 0 5px 10px black;
}
#app-mount .guilds-1SWlCJ .scrollerBase-289Jih > div[style]:not(.listItem-2P_4kh) {
  height: auto !important;
}
#app-mount .guilds-1SWlCJ .scrollerBase-289Jih > div[style]:not(.listItem-2P_4kh)[style*="height: 0px"] {
  padding-top: 1px;
}
#app-mount .guilds-1SWlCJ .svg-1X37T1,
#app-mount .guilds-1SWlCJ .wrapper-25eVIn,
#app-mount .guilds-1SWlCJ .guildsError-b7zR5H,
#app-mount .guilds-1SWlCJ .placeholderMask-3K9THS {
  width: var(--server-size);
  height: var(--server-size);
}
#app-mount .guilds-1SWlCJ [role=group] {
  height: auto !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] {
  transform: rotate(90deg) translateY(-50%);
  height: var(--server-size);
  width: 4px;
  top: calc(var(--server-size) / -1 + var(--server-size) / 2 - 8px) !important;
  margin-left: -2px;
}
#app-mount .guilds-1SWlCJ [class*=pill] span {
  height: 100% !important;
  width: 4px !important;
  transform: scale(0, 1) !important;
  transition: 0.15s ease !important;
  margin-left: 0;
  border-radius: 0 4px 4px 0;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 0"] {
  transform: scale(1, 0.24) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 1"] {
  transform: scale(1, 0.24) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 2"] {
  transform: scale(1, 0.24) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 3"] {
  transform: scale(1, 0.24) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 4"] {
  transform: scale(1, 0.24) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 5"] {
  transform: scale(1, 0.24) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 6"] {
  transform: scale(1, 0.24) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 7"] {
  transform: scale(1, 0.24) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 8"] {
  transform: scale(1, 0.24) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 9"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 10"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 11"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 12"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 13"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 14"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 15"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 16"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 17"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 18"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 19"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 20"] {
  transform: scale(1, 0.7) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 21"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 22"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 23"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 24"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 25"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 26"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 27"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 28"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 29"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 30"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 31"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 32"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 33"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 34"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 35"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 36"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 37"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 38"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 39"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ [class*=pill] span[style*="height: 40"] {
  transform: scale(1, 1) !important;
}
#app-mount .guilds-1SWlCJ .wrapper-sa6paO {
  height: var(--server-size) !important;
}
#app-mount .guilds-1SWlCJ .wrapper-21YSNc,
#app-mount .guilds-1SWlCJ .wrapper-3Njo_c {
  width: var(--server-container);
}
#app-mount .guilds-1SWlCJ [class*=listItem]:not([class*=listItemWrapper]) {
  width: var(--server-size);
  transform: rotate(90deg);
  margin: var(--server-spacing) 10px;
  position: unset;
}
#app-mount .guilds-1SWlCJ [class*=guildSeparator] {
  transform: rotate(90deg);
  width: var(--server-size);
}
#app-mount .guilds-1SWlCJ [class*=expandedFolderBackground] {
  width: var(--server-size);
  left: 50%;
  border-radius: 10px;
  transform: translateX(-50%);
}
#app-mount .guilds-1SWlCJ .folder-21wGz3 {
  background: transparent;
}
#app-mount .guilds-1SWlCJ.hidden-3dXt4k + .base-3dtUhz {
  top: 0 !important;
}
#app-mount [class*=listItemTooltip] {
  position: absolute;
  max-width: unset;
  white-space: nowrap;
  margin-left: calc(var(--server-size) / -1 - 20px);
  top: calc(var(--server-size) - 10px);
}
#app-mount [class*=listItemTooltip] [class*=tooltipPointer] {
  transform: rotate(180deg);
  top: -5px;
  right: unset;
  left: 13px;
  z-index: 1;
}
#app-mount .friendsOnline-2JkivW {
  position: absolute;
  transform: translate(-50%, 50%);
  top: calc(-50% + var(--server-spacing));
  left: calc(-50%);
  width: calc(var(--server-size) + var(--server-spacing));
  display: flex;
  justify-content: center;
}
#app-mount .guilds-1SWlCJ.content-Pph8t6, #app-mount .BF-folderSidebar {
  position: absolute !important;
  top: calc(var(--server-container) * 2) !important;
}
#app-mount .guilds-1SWlCJ.content-Pph8t6:not(.closed-j55_T-) + .base-3dtUhz, #app-mount .BF-folderSidebar:not(.closed-j55_T-) + .base-3dtUhz {
  top: calc(var(--server-container) * 2) !important;
}
#app-mount .guilds-1SWlCJ .frame-oXWS21[class*=listItem] {
  height: var(--server-size) !important;
}
#app-mount .guilds-1SWlCJ .frame-oXWS21[class*=listItem] .wrapper-1BJsBx {
  height: 100% !important;
}
#app-mount .guilds-1SWlCJ .frame-oXWS21[class*=listItem] .button-Jt-tIg {
  width: 100%;
  height: 100% !important;
  border-radius: 50%;
  padding: 2px;
  font-size: 10px;
  box-sizing: border-box;
  text-align: center;
}
#app-mount .BF-folderSidebar {
  top: calc(var(--server-container)) !important;
}

html.platform-osx #app-mount .typeMacOS-3EmCyP {
  width: 100%;
}
html.platform-osx #app-mount .base-3dtUhz {
  top: calc(var(--server-container) + 30px) !important;
}
html.platform-osx #app-mount #pluginNotice {
  top: 32px;
  z-index: 100000 !important;
}

body.foldercontentopened .base-3dtUhz {
  transition: 0.2s ease !important;
}

body #app-mount .app-1q1i1E .base-3dtUhz {
  top: 0 !important;
  bottom: var(--server-container) !important;
  border: 7px solid #24252673;
}
body #app-mount .guilds-1SWlCJ {
  top: unset !important;
  left: 100vw;
  bottom: 0 !important;
  transform-origin: bottom left;
}
body #app-mount .guilds-1SWlCJ.content-Pph8t6 {
  top: unset !important;
  bottom: var(--server-container) !important;
}
body #app-mount .guilds-1SWlCJ.content-Pph8t6:not(.closed-j55_T-) + .base-3dtUhz {
  top: 0 !important;
  bottom: calc(var(--server-container) * 2) !important;
}
body #app-mount .guilds-1SWlCJ [class*=pill] {
  top: unset !important;
  bottom: calc((var(--server-size) / -1) + (var(--server-size) / 2) - 8px) !important;
}
body #app-mount .guilds-1SWlCJ [class*=pill] span {
  border-radius: 4px 0 0 4px;
}
body #app-mount [class*=listItemTooltip] {
  position: absolute;
  white-space: nowrap;
  top: calc(var(--server-size) / -1 - 30px) !important;
  margin-left: calc(var(--server-size) / -1 - 20px);
}
body #app-mount [class*=listItemTooltip] [class*=tooltipPointer] {
  transform: rotate(0) !important;
  top: unset !important;
  bottom: -10px !important;
}

html.platform-osx #app-mount .base-3dtUhz {
  top: 32px !important;
  
}

#app-mount .guilds-1SWlCJ .scrollerBase-289Jih {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

/* Unread pill */
.unread-2lAfLh {
  padding-left: 0px;
}

/*Avatar only member list*/
.membersWrap-2h-GB4 {
  min-width: unset;
}
.membersWrap-2h-GB4 .members-1998pB {
  max-width: 65px;
  min-width: 65px;
  -webkit-transition: .3s ease;
  transition: .3s ease;
}
.membersWrap-2h-GB4 .members-1998pB:hover {
  max-width: 240px;
  min-width: 240px;
}
.membersWrap-2h-GB4 .members-1998pB .content-3YMskv:not(:hover) {
  padding-top: 10px;
}
.membersGroup-v9BXpm {
  transition: .3s ease;
}
.membersWrap-2h-GB4:not(:hover) .membersGroup-v9BXpm {
  height: 0px;
  opacity: 0;
  padding: 0%;
  transition: .3s ease;
}

/* Message bar */
.scrollableContainer-2NUZem {
  background: transparent;
}

/* Search menu */
.popoutBottom-2GAFPg.noArrow-2foL9g {
  margin-top: -1px !important;
}

.popout-3sVMXz.popoutBottom-1YbShG.noShadow-321ZPm[style*="top: 37px;"] {
  top: 46px !important;
}

.container-3ayLPN.elevationBorderHigh-2WYJ09 {
  margin-top: -8px !important;
}

.searchPopout-1vUlP3,
.container-3ayLPN {
  background-color: var(--background-primary) !important;
  border-radius: 0 !important;
  border: none !important;
  border-left: 2px solid var(--background-primary) !important;
  border-right: 2px solid var(--background-primary) !important;
  border-bottom: 2px solid var(--background-primary) !important;
}

.searchPopout-1vUlP3 .resultsGroup-r_nuzN,
.searchPopout-1vUlP3,
.container-3ayLPN {
  animation: popoutanim 300ms cubic-bezier(.4, 0, 0, 1), opacity 100ms ease 100ms backwards;
  transform-origin: 50% -10%;
  box-sizing: content-box;
}

.resultsGroup-r_nuzN .header-2N-gMV {
  background-color: var(--background-tertiary);
  padding: 10px 20px;
}

.resultsGroup-r_nuzN .searchClearHistory-2cSSMO,
.resultsGroup-r_nuzN .searchLearnMore-3SQUAj {
  top: 17px;
}

.option-96V44q,
.result-2S5Awv {
  border-left: 2px solid transparent;
  border-radius: 0px;
}

.option-96V44q:after,
.option-96V44q.selected-rZcOL-:after {
  display: none;
}

.queryContainer-RKFJW- {
  background-color: var(--background-tertiary) !important;
}

.option-96V44q.selected-rZcOL-,
.result-2S5Awv.focused-1Yu0L3 {
  background-color: var(--background-tertiary) !important;
  border-color: var(--background-secondary);
}

.option-96V44q.searchQuery-1B7rtx.selected-rZcOL-,
.queryContainer-RKFJW- {
  border-color: transparent;
}

.dim-1l4L4y span {
  background-color: var(--background-primary) !important;
  color: white !important;
}

.option-96V44q span {
  overflow: visible;
}

/* Misc. */
.toolbar-1t6TWx a {
  display: none
} /* Help icon on titlebar */

#app-mount .mentioned-xhSam7:before {
	background-color: #6580cf6e;
	padding: 1px; 
	}
#app-mount .mentioned-xhSam7 {
	background-color: #6580cf17;
	} 
  
.theme-dark .wrapper-3WhCwL {
  color: rgb(255, 255, 255);
  background-color: #43d3dd4b;
} /* Mention colour */

/* Speed acceleration - Tropical#4355*/
.layer-3QrUeG {
  transform: none !important;
  opacity: 1 !important;
}

.layers-3iHuyZ>.layer-3QrUeG.animating-rRxada *,
.layers-3iHuyZ>.layer-3QrUeG.animating-rRxada {
  pointer-events: auto !important;
  will-change: unset;
}

.animating-rRxada.stop-animations {
  z-index: 100 !important;
}

/* Resizeable channel list/DM list */
:root { --sidebar-initial-width: 200px; }
.sidebar-2K8pFh {
    resize: horizontal;
    width: var(--sidebar-initial-width);
}
.sidebar-2K8pFh .channel-2QD9_O { max-width: unset; }
.bannerImage-3KhIJ6 { width: 100%; }
