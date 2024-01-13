# Szenario: Stromausfall

1. Unwetterwarnung Deutscher Wetterdienst
2. DWD Live Wetterdaten
3. Blitzeinschlag in einem Firmengebäude
4. BMA löst aus -> Alarm in der ILS
5. Stromausfall | Infoquellen: R1
6. Priosierung nach Einsatzwahrscheinlichkeit
7. Örtlichkeit = Koordinaten Blitzwahrscheinlichkeit
8. 

## Ressourcen
- R1: https://störungsauskunft.de/
- R2:

## Datenquellen
- Blitzortung.org
  Datasource: Websocket wss://ws1.blitzortung.org
  {"time":1705103ĉ8Đ93Ċ600,"latĆ43.334669ĘlonĆ-79.87Ģ16ĘalĜ:ė"polĆĺmdsĆ1Ĉ4ŀcgĆ98ĘstěuŃćĘregiĩĿŎiŊ:[Āŏań1ĐĘĂĄĆ2158ċħěĝğ7Ů95ħŚ:ĬĮ3Ĥ592ĵķń54ŎŐtŒń0},šŐŪ5ūŧăą:32ſĳŰĸĞį8ĥůęŹĬ8.945ıƁ"Ķĸ97Ƈőœ12ƍƏţćĳƬŨƖ7ĈĎĴęű:42Ƨ9ĕ4ōƣĪź8Ǉģǆ5ǂƮńŦ"ŢƉƴƌƎǙƐƺ2ǌƽĆƿƠ7ƬĚƝǇ681ƩǌĨǎĬ7ĠĭƙƂǫƱǟƳƋƷǼŪİƼƕŋĈ261ƜĝǇċ74ȉǍī76.ƿ06ǻǖƗƅƲǛńƶǞŢńŶȐǤć0ƿċĺǪĝȔ19ČǐŸǳĭĠƀƨƆƭƃ:2ȏȝƊćȠƸńıǻȦŬƙ08ȫǄƞ0ƨĭȐǲīŮ.ģȓƓȺĸȇĦǼȞɁǿȢćĒ3Ɣũć5ƪǋǱɍ1ĠƙŮɒƤȎƧūưȹȚŇǌǚɀƵɡǠȇťɦƖĳƒŌǩɍ4Ġ6ſȗȳȒğ9čĊɥɚń4ƨȿƴɂȀȼ3Ƣɇĉ6ģŷǃĸ3Įɏ83ƛȑź7ǵƒ2ȗɸȻČǻɼʛɿƹŅǭʃǗ4ƩʾʦĝʊƅƩĭʏʯğʳȇǕȻſʚǾȡʀƅʥɇŮʫ2ʈƝʊ6Ǣ9ɝɓˋ.ȯǯɝȚĒ˒ɠ˔ƹ2ĉɝȦū2ȰĊȊǅɮȏǭƢˣ-İ˥5ŽʂʖʞɝʹȟʻƑǋʿȼ1ʨ2Ƙ˷ǆɖ0ȇȇˊĬȌŬɏȐȚȱ˫4̉̍ɩ̌˛˯̕ʥȬƗǵĎģŬ̘ɋ.ƒƵ̕ǹŤɋ˫ɾ˭Ťı̥Ƙ˺ˢɍȌĐ̎ɲȴ˹ČʣʥȚȲɞɽǝɃȼŶĺ˲ŽɩǨ̒Ǉˠ8ˢɳɮʟŽ˛̶:Ȉ̢̠ǯʨ̥ˁɰɬʧƦ˛Ņǘ˽8ʊǮȎ˴ͣ˛ǂ̇ǅͧǉ˱ȄȼƩƀ0ɒɍĮ7ċǮǂ˽ʰ.˟čˡ͹ˑ͎ʺ̻΂Ʃ̥˚ĭʕ̪ȏΏ6ƘȜʮĬ0˥ŬĢ˨ʶͻƈɀ̡Ηťʹ̌Ďċǭ́ƝĮ̎ǨΙΤǭ˥ǉʪͣȯͦ]ĘdeĚyĝ.ǩĩcśʦϏĹ}

- DWD-Daten

  Datasource: WebFeatureService  (WFS)
  
  ![DWD01](https://github.com/FeuerwehrHackathon2024/FireLake/assets/132459493/e43e322a-451c-44df-a203-ff008d3ac5f5)

- Störungsauskunft.de

  API-Public liefert JSON api-public.stoerungsauskunft.de (Header Authorization Basic ZnJvbnRlbmQ6ZnJvbnRlbmQ=)
 
