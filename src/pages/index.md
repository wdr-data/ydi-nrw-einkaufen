---
title: "Einkaufen in NRW - Was schätzen Sie?"
description: Non adipisicing minim magna anim esse consectetur amet ex dolore amet veniam.
author: Peter Schneider
pub_date: "2021-10-08"
heroImage: "richard-wagner-und-freunde.jpg"
heroAlt: "Richard Wagner und seine Freunde"
heroCredit: "Richard Wagner und seine Freunde"
sharingImageFacebook: "richard-wagner-und-freunde_facebook.jpg"
sharingImageTwitter: "richard-wagner-und-freunde_twitter.jpg"
cg1: "WDR"
cg2: "Data"
cg3: "WDR 3"
cg4: "Opern-Spielpläne in NRW: tot und männlich"
---

import DataWrapper from '../components/datawrapper/datawrapper.jsx'
import Quote from '../components/quote/quote.jsx'
import Webtrekk from '../components/webtrekk/webtrekk.jsx'
import Sharing from '../components/sharing/sharing.jsx'
import YDIBar from '../components/ydi/ydiBar.jsx'
import YDILine from '../components/ydi/ydiLine.jsx'
import { Link, LinkList } from '../components/link/link.jsx'

# NRW Einkaufen

## Einkaufen in NRW? Was schätzen Sie?

Cupidatat sit commodo reprehenderit aute. In commodo ad Lorem esse aliqua sint cillum id esse commodo commodo. Ex labore exercitation non veniam laborum Lorem veniam incididunt tempor non incididunt exercitation. Do deserunt voluptate id irure excepteur. Quis Lorem ipsum Lorem aliqua eiusmod.

## Beispiel WSS Line Chart:

<YDILine name="line"/>

## Beispiel WSS Bar Chart:

<YDIBar name="bar"/>


### Consectetur irure incididunt tempor esse sit.

<Link title="Dies ist ein Beispiel für einen einzelnen Link" href="https://example.com/" />

<LinkList links={[
    {
        title: "Dies ist ein Beispiel für eine Link-Liste",
        href: "https://example.com/",
    },
    {
        title: "Dies ist noch ein Beispiel für eine Link-Liste",
        href: "https://example.com/",
    },
]} />

<figure role="group">
    <figcaption>Wurde das Stück im Haus auch 'für Kinder' gespielt, haben wir es hier mit zusammengefasst.</figcaption>
    <DataWrapper
        alt="76 mal wurde die Zauberflöte 2018/2019 in NRW aufgeführt, gefolgt von Hänsel und Gretel mit 34 Aufführungen."
        title="Zauberflöte vor Hänsel und Gretel"
        src="//datawrapper.dwcdn.net/azwpu/7/"
    />
</figure>

<figure role="group">
    <img src="berthold-schneider-credit-jens-grossmann.jpg" alt="Der Wuppertaler Opernintendant Berthold Schneider, fotografiert von Jens Grossmann" />
    <figcaption style="text-align: end;">Berthold Schneider</figcaption>
</figure>

<Quote author="Hambone Fakenamington">Ullamco consequat adipisicing eiusmod duis velit excepteur qui eiusmod.</Quote>

<Sharing twitter facebook mail whatsapp telegram reddit xing linkedin />
