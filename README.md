.room-background {
    background: url(http://www.part.lt/img/a56355014699ceef5285b543b7a33249779.jpg) no-repeat !important;
    width: 500% !important;
    height: 500% !important;
}
/* Rainbow DinÃ­k */
#user-rollover.id-5383370 .username:hover,
#chat [data-cid^="5383370"] span.un.clickable:hover {
animation:rainbow 10s infinite;
}
@keyframes rainbow {
0% {color: #ff0000;}
10% {color: #ff8000;}
20% {color: #ffff00;}
30% {color: #80ff00;}
40% {color: #00ff00;}
50% {color: #00ff80;}
60% {color: #00ffff;}
70% {color: #0080ff;}
80% {color: #0000ff;}
90% {color: #8000ff;}
100% {color: #ff0080;}
}
/* End Rainbow DinÃ­k */
#footer {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.45) 0,rgba(0, 0, 0, 0.75) 100%);
}
#footer-user .info.showing .meta .bar .progress {
	background:#2D9400;
}
#footer-user .info.showing .meta .level .label {
	color:#EFEFEF;
}
#footer-user .info.showing .meta .level .value {
	color:#EFEFEF;
}
#footer-user .info.is-staff.showing .name {
	color: #0EB006;
}
#footer .shop-button {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.45) 0,rgba(0, 0, 0, 0.75) 100%);
}
#footer-user .info.showing {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.55) 0,rgba(0, 0, 0, 0.85) 100%);
}
#chat {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.20) 10%,rgba(0, 0, 0, 0.65) 100%);
}
#chat .emote, #chat .mention, #chat .message, #chat .moderation, #chat .skip, #chat .system, #chat .update, #chat .welcome, #chat .user-action {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.20) 10%,rgba(0, 0, 0, 0.65) 100%);
}
#room .app-right {
	background: linear-gradient(to left,rgba(0, 0, 0, 0.20) 10%,rgba(0, 0, 0, 0.65) 100%);
}
.welcome .text {
	color:cyan;
}
.group.host {
	color:#3083FF;
}
i.icon.icon-chat-host {
	background : url(https://dinikcz.github.io/CM-CCS/plug/SM-Host.png);
}
.group.manager {
	color:#FF3030;
}
i.icon.icon-chat-manager {
	background : url(https://dinikcz.github.io/CM-CCS/plug/SM-Manager.png);
}
.group.bouncer {
	color:crimson;
}
i.icon.icon-chat-bouncer {
	background : url(https://dinikcz.github.io/CM-CCS/plug/SM-Bouncer.png);
}
.group.dj {
	color:#ac76ff;
}
i.icon.icon-chat-dj {
	background : url(https://dinikcz.github.io/CM-CCS/plug/SM-Resdj.png);
}
#user-rollover .info .level .label {
	color:#EFEFEF;
}
#user-rollover.is-staff .info .role span {
	color: #0EB006;
}
#vote {
	box-shadow: 0 0 10px #000;
	border-radius: 40px;
	width: 255px !important;
}
#app #vote .bottom {
	background: rgba(0,0,0,0);
}
#woot, #grab, #meh {
	margin-top: 0 !important;
}
#vote .selected,
#vote .selected .value {
	font-weight: bold;
	color: #FFF;
}
.pop-menu, .pop-menu .bar {
	border-radius: 20px 20px 0 0;
	background: transparent;
}
.pop-menu .bar {
	background: linear-gradient(hsla(260,50%,50%,.8), hsla(260,50%,30%,.8));
}
.pop-menu .bar-divider {
	background: linear-gradient(hsla(0,0%,90%,.8), hsla(0,0%,60%,.8));
}
.pop-menu .menu ul {
	background: hsla(260,10%,7%,.8);
}
.pop-menu .menu ul i + span {
	font-weight: bold;
}
.pop-menu .menu ul li:hover {
	background: linear-gradient(hsla(260,50%,50%,.2), hsla(260,50%,30%,.2));;
}
.pop-menu .menu ul .create:hover {
	background: linear-gradient(hsl(260,40%,50%), hsl(260,40%,30%));
}
.pop-menu .menu::-webkit-scrollbar {
	background: hsl(260,10%,20%) !important;
	box-shadow: inset 0 0 10px #000;
	width: 10px;
}
.pop-menu .menu::-webkit-scrollbar-thumb {
	background: linear-gradient(to right, hsl(260,40%,60%), hsl(260,40%,40%));
	box-shadow: inset 0 0 5px hsla(0,0%,100%,.3);
}
#woot {
	border-radius: 30px 0 0 30px;
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.45) 0,rgba(0, 0, 0, 0.75) 100%) !important;
	box-shadow: inset 0 0 10px hsl(0,0%,40%) !important;
}
#woot.selected, #woot-rs .title {
	background: linear-gradient(135deg, hsla(90,80%,50%,.3), hsla(90,80%,30%,.3)) !important;
	box-shadow: inset 0 0 10px hsl(70,100%,40%) !important;
}
#grab {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.45) 0,rgba(0, 0, 0, 0.75) 100%) !important;
	box-shadow: inset 0 0 10px hsl(0,0%,40%) !important;
}
#grab.selected, #grab-rs .title {
	background: linear-gradient(hsla(270,70%,50%,.3), hsla(265,70%,30%,.3)) !important;
	box-shadow: inset 0 0 10px hsl(280,100%,40%) !important;
}
#meh i.icon {
    background-image: url("http://imgur.com/a/oS7wS");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
}
#woot i.icon {
    background-image: url("http://imgur.com/BAjiYAW");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
}
#grab i.icon {
    background-image: url("http://imgur.com/a/Zohx8");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
}
#meh {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.45) 0,rgba(0, 0, 0, 0.75) 100%) !important;
	box-shadow: inset 0 0 10px hsl(0,0%,40%) !important;
	border-radius: 0 30px 30px 0;
	margin-right: 0 !important;
}
#meh.selected, #meh-rs .title {
	background: linear-gradient(225deg, hsla(5,80%,50%,.3), hsla(0,80%,40%,.3)) !important;
	box-shadow: inset 0 0 10px hsl(15,100%,50%) !important;
}
#dj-button.is-wait, #dj-button.is-leave, #dj-button.is-quit, #dj-button.is-locked, #dj-button.is-full {
	opacity: 0.85;
}
#dj-button, #dj-button.is-leave { 
	border-radius: 10px 10px 10px 10px;
	background: linear-gradient(to top,#3A3A3A,rgba(34, 34, 34, 1) 100%);
}
#dj-button .left {
	border-radius: 10px 10px 10px 10px;
	background: linear-gradient(to top,#14C0F3,rgba(0, 152, 196, 1) 100%);
}
#dj-button.is-leave .left {
	background: linear-gradient(to top,#F3653D,rgba(228, 61, 13, 1) 100%);
}
.torch {
	visibility: hidden;
}
.is-staff .name {
	color: #00FFF7;
    font-weight: normal;
}
#chat .from.staff .un {
	color: #00FFF7;
    font-weight: normal;
}
.user-content.profile .meta.is-staff .role span {
	color: #00FFF7;
    font-weight: normal;
}
#user-rollover.is-staff .info .role span {
	color: #00FFF7;
    font-weight: normal;
}
#playlist-button {
    background: linear-gradient(to bottom,#00FFEB 0,#0075C8 100%);
}
.app-header {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.9) 0,rgba(0, 0, 0, 0.9) 100%);
}
#app-menu {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 1) 0,rgba(61, 61, 61, 1) 100%);
}
#rs-skip-button {
	background: none !important;
}
#history-button {
	background: none;
}
.header-panel-button.selected {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 1) 0,rgba(61, 61, 61, 1) 100%);
}
#user-rollover {
	border-radius: 30px 30px 0 0;
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.45) 0,rgba(0, 0, 0, 0.75) 100%);
	box-shadow: 0 0 10px #000;
}
#user-rollover .info {
	background: linear-gradient(rgba(230,255,0,0.45), rgba(255,179,0,0.45));
	box-shadow: 0px -2px 10px -1px #000;
	border-radius: 50% 50% 0 0 !important;
}
.thumb {
	background: hsla(210,10%,10%,.4);
}
#user-rollover .info .badge-box,
#user-rollover .background,
#video-only-dj .background,
#search-suggestion,
#search-suggestion ul {
	background: rgba(0,0,0,0);
}
.thumb.large, .thumb, #user-rollover .meta.online .thumb {
	border-color: hsl(80,70%,50%) !important;
	box-shadow: 0 0 7px hsl(80,70%,50%) !important;
}
.thumb.large, #user-rollover .meta.online .thumb.large {
	box-shadow: 0 0 15px hsl(80,70%,50%) !important;
}
#user-rollover.is-staff .meta.online .thumb, #waitlist .is-staff .thumb {
	border-color: hsl(270,50%,50%) !important;
	box-shadow: 0 0 7px hsl(270,50%,50%) !important;
}
#user-rollover.is-staff .meta.online .thumb.large {
	box-shadow: 0 0 15px hsl(270,50%,50%) !important;
}
#user-rollover .meta.subscriber .thumb, #waitlist .is-subscriber .thumb {
	border-color: hsl(45,80%,45%) !important;
	box-shadow: 0 0 7px hsl(45,80%,45%) !important;
}
#user-rollover .meta.subscriber .thumb.large {
	box-shadow: 0 0 15px hsl(45,80%,45%) !important;
}
#user-rollover .meta.online .status i {
	display: none;
}
#user-rollover .meta.online .status span {
	color: hsl(80,70%,50%);
	margin-left: 0;
}
.offline .thumb {
	border-color: hsl(0,0%,40%) !important;
	box-shadow: none !important;
}
#user-rollover .action {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.45) 0,rgba(0, 0, 0, 0.75) 100%) !important;
	box-shadow: 0 0 2px 1px #151515 !important;
}
#user-rollover .action:hover {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.45) 0,rgba(0, 0, 0, 0.75) 100%) !important;
	box-shadow: inset 0 0 50px #000 !important;
}
#playlist-panel {
	background: linear-gradient(to bottom,rgba(0, 0, 0, 0.9) 0,rgba(0, 0, 0, 0.9) 100%) !important;
}
#playlist-menu {
	background: none;
}
.media-list .row.selected {
	background: #00ACAC !important;
}
#playlist-menu .menu .row.selected {
	background: #00ACAC !important;
}
#playlist-menu .menu .row .count {
	color: #FFFFFF !important;
}
#search {
	background: none !important;
}
#search-bar {
	background: none !important;
}
.media-list .selected .actions {
	background: #007D7D !important;
}
.media-list .row .now-playing {
	background: #00ACAC !important;
}
#playlist-edit-button {
	background: none;
}
#playlist-shuffle-button {
	background: none;
}
#playlist-delete-button {
	background: none;
}
.experience .xp .bar .progress {
    border-color: hsl(198,80%,45%) !important;
	box-shadow: 0 0 7px hsl(198, 80%, 45%) !important;
}
#playlist-import {
	background: none;
}
#playlist-create {
	background: none;
}
#chat-input {
	border-radius: 30px 0 0 30px !important;
}
#app-menu, #app-menu .list {
    background: linear-gradient(to bottom,rgba(0, 0, 0, 0.9) 0,rgba(0, 0, 0, 0.9) 100%) !important; 
}
#dj-button.is-leave .left, #dj-button.is-quit .left {
    background: linear-gradient(to bottom,rgba(244, 107, 64, 1),rgba(244, 107, 48, 1) 100%) !important;
}
#chat .emote .text {
    font-style: normal;
    font-weight: bold;
    color: rgb(172, 118, 255);
}
#chat .emote {
    border-left: #AC76FF 2px solid;
}
.message.role-bouncer, .emote.role-bouncer {
    border-left: crimson 2px solid;
}
.message.role-host, .emote.role-host {
    border-left: #3083FF 2px solid;
}
.message.role-cohost, .emote.role-cohost {
    border-left: #3083FF 2px solid;
}
.message.role-dj, .emote.role-dj {
    border-left: #ac76ff 2px solid;
}
.message.role-manager, .emote.role-manager {
    border-left: #FF3030 2px solid;
}

/* DinÃ­k */
#user-rollover.id-5383370 .badge-box > i.bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/dinikcz.gif");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
[data-cid^="5383370"] .badge-box .bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/dinikcz.gif");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
/* End DinÃ­k */

/* Pandis */
#user-rollover.id-13994689 .badge-box > i.bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/pandis.gif");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
[data-cid^="13994689"] .badge-box .bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/pandis.gif");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
/* End Pandis */

/* Herkul */
#user-rollover.id-26869640 .badge-box > i.bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/herkul.gif");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
[data-cid^="26869640"] .badge-box .bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/herkul.gif");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
/* End Herkul */

/* DenisJ */
#user-rollover.id-5726279 .badge-box > i.bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/denisj.jpg");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
[data-cid^="5726279"] .badge-box .bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/denisj.jpg");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
/* End DenisJ */

/* TegBot */
#user-rollover.id-21723824 .badge-box > i.bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/tegbot.gif");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
[data-cid^="21723824"] .badge-box .bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/tegbot.gif");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
/* End TegBot */

/* FirennCZ */
#user-rollover.id-14171432 .badge-box > i.bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/firenn.gif");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
[data-cid^="14171432"] .badge-box .bdg
{
    border-radius:       6px;
    background-image:    url("https://dinikcz.github.io/CM-CCS/plug/firenn.gif");
    background-size:     cover;
    background-repeat:   no-repeat;
    background-position: center center;
}
/* End FirennCZ */
