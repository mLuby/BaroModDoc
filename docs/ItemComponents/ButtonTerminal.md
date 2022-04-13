# ButtonTerminal


## Example
```xml
<Item name="" identifier="alienterminal" category="Alien" Tags="smallitem,logic" cargocontaineridentifier="metalcrate" scale="0.5" impactsoundtag="impact_metal_light" isshootable="true">
  <ButtonTerminal activatingitems="smallalienartifact" canbeselected="true" msg="ItemMsgInteractSelect">
    <GuiFrame relativesize="0.25,0.2" style="ItemUI" anchor="Center" />
    <TerminalButton style="alienbuttongreen" />
    <TerminalButton style="alienbuttonred" />
  </ButtonTerminal>
  <ItemContainer capacity="1" canbeselected="true" hideitems="true" slotsperrow="1" uilabel="" allowuioverlap="true">
    <Containable items="smallitem" />
  </ItemContainer>
  <ConnectionPanel selectkey="Action" canbeselected="true" hudpriority="10">
    <GuiFrame relativesize="0.2,0.32" minsize="400,350" maxsize="480,420" anchor="Center" style="ConnectionPanel" />
    <RequiredItem identifier="screwdriver" type="Equipped" />
    <output name="signal_out1" displayname="connection.signaloutx~[num]=1" />
    <output name="signal_out2" displayname="connection.signaloutx~[num]=2" />
  </ConnectionPanel>
  [...]
</Item>
```
