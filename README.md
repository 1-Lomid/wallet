# wallet
WALLETADDRESS="" APPNAME=helloworld_"${WALLETADDRESS:4:6}" echo $APPNAME leo new "${APPNAME}" cd "${APPNAME}" &amp;&amp; leo run &amp;&amp; cd - PATHTOAPP=$(realpath -q $APPNAME) echo $PATHTOAPP cd $PATHTOAPP &amp;&amp; cd ..
