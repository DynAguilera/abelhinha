@import url("https://rawgit.com/BotFarofa/farofatheme/master/alter.css");

#room-bar .icon-room {
    background: url(http://i.imgur.com/SpyEMvS.png);
.icon {
    width: 30px;
    height: 30px;
}

#room-name, #room-host {
    left: 89px !important;
    color: #fff !important;
    font-weight: bold;
    text-shadow: 2px 0px 11px, #dd00ff;
    background: url(http://forum.ragezone.com/images/backround6.gif);
}

.dark-label {
    color: #fff !important;
    font-weight: null;
    text-shadow: 2px 0px 11px, #dd00ff;
    background: url();
    
}
#dj-button {
    background: rgba(34, 34, 36, 0.59);
    border-radius: 8px;
}
#dj-button .left  {
    background: #aa74ff !important;
}
#vote .top {
    background: rgba(34, 34, 36, 0.4) !important;
}

#room .app-right {
    background: linear-gradient(to right,rgba(0, 0, 0, 0.70) 0,rgba(0, 0, 0, 1) 100%);
}
.app-header {
    background: rgba(28, 31, 37, 0.59);
}
/*
#playback-container {
    background-image: url();
    background-position: center;
    background-size: 100% auto;
}

#chat .message:nth-child(2n+1) #chat .mention:nth-child(2n+1) #chat .skip:nth-child(2n+1) #chat .moderation:nth-child(2n+1) #chat .emote:nth-child(2n+1) #chat .update:nth-child(2n+1) #chat .welcome:nth-child(2n+1) {
    background-color: rgba(17 19 23 0.32);
    -webkit-animation: fadein 0.25s;
    -moz-animation: fadein 0.25s;
    -ms-animation: fadein 0.25s;
    -o-animation: fadein 0.25s;
    animation: fadein 0.25s;
    animation: fadein 0.25s;
    background-color: #111317;
    border-radius: 0px;
    background-color: rgba(17 19 23 0.5);
}

#chat #chat-input {
    background: rgba(80 80 80 0.25);
}

.icon-chat-host > span {
    color: #FF3558 !important;
}

#playlist-panel {
    opacity: .85;
}

#footer {
    background-color: rgba(30 30 36 1) !important;
}

#playback-controls .button.snooze {
    background: #00afe4 !important;
    opacity: .7;
}

#playlist-button {
    background: #FF3558 !important;
}

#playlist-menu .menu .row.selected {
    background: #39688D !important;
}

.media-list .row.now-playing {
    background: #FF3558 !important;
    border-bottom: 1px solid #ff5f7c !important;
}

#playlist-menu .menu .row .count {
    color: #FF3558 !important;
}

#grab .bottom #grab.selected {
    background: #00afe4 !important;
}

#footer-user .bar .progress {
    background: #FF3558 !important;
}

.experience .xp .bar .progress {
    background: #FF3558 !important;
}

.activate-button span {
    color: #FFFFFF !important;
}

#playlist-activate-button {
    background: none !important;
}

#playlist-activate-button span {
    color: #FF3558 !important;
}

.media-list .row.now-playing .actions {
    background: #FF3558 !important;
}

.media-list .row.selected {
    background: #39688D !important;
}

.media-list .selected .actions {
    background: #FF3558 !important;
}

#user-lists .header .button.staff.selected {
    border-bottom: 1px solid #FF3558 !important;
}

.dialog.destructive .button.submit {
}

#room-info .button.disabled {
    background: #FF3558 !important;
}

#room-info .button.enabled {
    background: #00afe4 !important;
}

#playlist-create:hover {
    background: #0191ff !important;
}

#playlist-import:hover {
    background: #0191ff !important;
}

#playlist-edit-button:hover {
    background: #0191ff !important;
}

#playlist-shuffle-button:hover {
    background: #0191ff !important;
}

#playlist-delete-button:hover {
    background: #c42e3b !important;
}

.tab-menu button.selected {
    background: #FF3558 !important;
}

#dj-button .left {
    background: #00afe4 !important;
}

#dj-button.is-leave .left {
    background: #FF3558 !important;
}

#dj-button.is-quit .left {
    background: #FF3558 !important;
}

.delete-button:hover {
    background: #FF3558 !important;
}

.icon-plug-dj {
    display: none;
}

#chat .icon .icon-p3 {
    background-image: url('') !important;
}

.icon-chat-ambassador + span {
    color: #89be6c !important;
}

.icon-chat-host + span {
    color: #FF3558 !important;
}

.icon-chat-cohost + span {
    color: #FF3558 !important;
}

.icon-chat-manager + span {
    color: #0191ff !important;
}

.icon-chat-bouncer + span {
    color: #01e1ff !important;
}

.icon-chat-dj + span {
    color: #89BE6C !important;
}

#chat .emote #chat .mention #chat .message #chat .moderation #chat .skip #chat .system #chat .update #chat .welcome {
    -webkit-animation: fadein 0.25s;
    -moz-animation: fadein 0.25s;
    -ms-animation: fadein 0.25s;
    -o-animation: fadein 0.25s;
    animation: fadein 0.25s;
}

#chat .moderation, #chat .moderation .from .un{
    color: #01e1ff;
}

#chat .message:hover #chat .emote:hover #chat .update:hover {
    -moz-transition: 100ms linear 50ms;
    -o-transition: 100ms linear 50ms;
    -webkit-transition: 100ms linear 50ms;
    border-left: #FFFFFF 1px solid;
    padding-left: 1px;
    text-decoration: none;
    transition: 100ms linear 50ms;
}

#chat .moderation:hover {
    -moz-transition: 100ms linear 50ms;
    -o-transition: 100ms linear 50ms;
    -webkit-transition: 100ms linear 50ms;
    border-left: #FF7676 1px solid;
    padding-left: 1px;
    text-decoration: none;
    transition: 100ms linear 50ms;
}

#chat .message:nth-child(2n+1)#chat .mention:nth-child(2n+1)#chat .skip:nth-child(2n+1)#chat .moderation:nth-child(2n+1)#chat .emote:nth-child(2n+1)#chat .update:nth-child(2n+1)#chat .welcome:nth-child(2n+1) {
    background-color: rgba(17 19 23 1.0);
    -webkit-animation: fadein 0.25s;
    -moz-animation: fadein 0.25s;
    -ms-animation: fadein 0.25s;
    -o-animation: fadein 0.25s;
    animation: fadein 0.25s;
}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}

@-moz-keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}

@-webkit-keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}

@-ms-keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}

@-o-keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}

.drag-media-box {
    background-color: #FF3558
}

body {
    background-size: 100% auto !important background-attachment: fixed 0px 0px !important
}

/* cabeçalho alternativo */

.app-header {
    background: rgba(28, 31, 37, 0.59); !important;
}

