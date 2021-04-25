@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');


* {
    --background-primary: transparent;
    --background-secondary: transparent;
    --background-secondary-alt: transparent;
    --background-tertiary: transparent;
    --background-accent: transparent;
    /* MENTION CIRCLE(default discord: red and white text) and background for mentioned messages */
    --mention-circle-color: rgba(100,100,10,0.9);
    --mention-circle-text-color: white;
    --mention-message-color: rgba(255, 255, 0, 0.25);

    /* color shades used for UI in all places */
    --darker-shade: rgba(10,10,25,0.80);
    --lighter-shade: rgba(10,25,25,0.49);

    /* used for #<autocomplete> menu */
    --background-color: rgba(10,10,10,0.95);

    /* emoji blur for diabled emojis(set to 0px if you dont want the blur) */
    --blur-radius: 5px;

    /* self explanatory */
    --text-color: white;
    --reply-color: yellowgreen;
    --shadow-color: black;

    /* defines how rounded is the icon */
    --server-logo-radius: 15px;

    /* background for calling(--call-background) and whole discord backgound(--background) */
    --call-background: linear-gradient(to bottom left, violet, indigo, blue, green, yellow, orange, red);
    --background: url("https://i.pinimg.com/originals/0a/4d/cb/0a4dcb92fa2d3c601b58d72720d6bec4.jpg");
}


body { 

  font-family: 'Zen Dots', monospace !important;


  background: var(--background) no-repeat center center fixed;
  background-size: cover;
}


.emojiItemDisabled-1FvFuF{
  filter: blur(var(--blur-radius)) !important;
}


.autocomplete-1vrmpx, .autocomplete-3l_oCd, .contentWrapper-SvZHNd {
  background: var(--background-color) !important;
  border-radius: 5px;
}



.scrollableContainer-2NUZem, .webkit-HjD9Er, .peopleList-3c4jOR, .nowPlayingColumn-2sl4cE, .container-1r6BKw {
  background: var(--lighter-shade) !important;
}


.da-messageGroupBlocked {
  display: none !important;
}


.wrapper-3NnKdC .scroller-1Bvpku .wrapper-25eVIn foreignObject {
  -webkit-mask: none;
          mask: none;
  border-radius: calc(var(--server-logo-radius) - 4px);
}





.messageGroupBlocked-3wrQQX ,
.messageGroupBlockedBtn-1PBBh- {
  display:none !important;
}

.messageContent-2qWWxC {
  color: var(--text-color);
  mix-blend-mode: difference;
}

.scrollbarGhostHairline-1mSOM1, .scrollbar-3dvm_9, .hljs {
  background: var(--lighter-shade) !important;
  box-shadow: 10px 10px 20px 5px black;
}

.userPopout-3XzG_A, .footer-1fjuF6, .container-2fRDfG, .wrapper-35wsBm, .background-1QDuV2, .inner-1ilYF7, .menu-3sdvDG {
  background: var(--darker-shade) !important;
  border-radius: 10px;
}

.body-3iLsc4 {
  background: var(--darker-shade) !important;
  border-radius: 0px;
}


.member-3-YXUe[data-user-id="465414607767339011"] .nameAndDecorators-5FJ2dg::after {
    display: inline-block;
    content: "";
    
    width: 16px;
    height: 16px;
    margin-left: 4px;
    
    background: url("https://raw.githubusercontent.com/DevItsMB/DevItsMB/master/verified_developer_badge.png") center / 100% 100%;
}




.repliedMessage-VokQwo::before {
  background: var(--reply-color) !important;
  border-radius: 10px;
}

.repliedMessage-VokQwo {
  z-index: 1;
}

.mentioned-xhSam7 {
  z-index: 0;
  background-color: var(--mention-message-color) !important;
}



.botTag-3W9SuW {
  background-color: green;
  color: white;
}


.embedWrapper-lXpS3L, .embedFull-2tM8--, .embed-IeVjo6, .wrapper-2aW0bm, .form-26zE04 {
  background: rgba(10,10,25, 1) !important;
}


.containerDefault--pIXnN{
  background: rgba(0,0,0, 0.25);
  box-shadow: 0px 0px 1000px;
}


.messageAttachment-1aDidq {
  box-shadow: 10px 10px 10px var(--shadow-color);
}


.unreadBar-3t3sYc[aria-hidden="false"] {
  background: var(--lighter-shade) !important;
  color: var(--text-color) !important;
  border-radius: 10px !important;
}


.headerNormal-T_seeN, .header-2BwW8b {
  background: linear-gradient(45deg, red, yellow) !important;
}


.activityUserPopout-2yItg2 {
  background: linear-gradient(to top right, red, blue);
}


.wrapper-2a6GCs {
  box-shadow: 0px 0px 50px var(--shadow-color);
  margin: 10px;
  border-radius: 10px;
  padding-top: 1px !important;
  padding-bottom: 1px !important;
  color: var(--text-color) !important;
}

.scrollerSpacer-avRLaA {
  margin: 0px;
}


.inlineCode-2ngu6Y, .inline {
  background: rgba(10,10,25, 1) !important;
  border-radius: 5px !important;
  box-shadow: 7px 7px 20px 5px black;
}

.mention {
  background: rgba(10,25,50, 1);
}

.messagesPopoutWrap-1MQ1bW {
  background: rgba(10,10,25, 1);
}

.root-217Brm {

   background-image: var(--call-background);  

  /*
  background: transparent;
  */
}

.staticButton-1B0rfQ, .centerButton-3CaNcJ, .colorable-1bkp8v, .white-3GPOIp, .button-38aScr, .lookBlank-3eh9lL, .colorBrand-3pXr91, .grow-q77ONN {
  background: transparent !important;
}

.numberBadge-2s8kKX, .base-PmTxvP, .baseShapeRound-1Mm1YW {
  background: var(--mention-circle-color) !important;
  color: var(--mention-circle-text-color);
}


.wrapper-1BJsBx {

  box-shadow: 11px 12px 20px 0px black !important;
  background: transparent;
  border-image-slice: initial;
  outline-color: transparent !important;
  border-radius: 0% im !important;
}


