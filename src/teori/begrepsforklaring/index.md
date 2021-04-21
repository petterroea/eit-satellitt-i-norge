---
title: Begrepsforklaring
layout: guide
collection: theory
---

# Begrepsforklaring

## Signalstyrke

Satellittsignaler måles i dBm. dB står da for “desibel”. Signalet mister mye av styrken sin innen det når mottakeren din, så det er viktig å forsterke det mest mulig. (Solidsignal, u.å.) Man kan regne ut amplituden til signalet ved å se på signalstyrken i dB, eller så kan man søke opp ulike tabeller på nettet. På denne siden kan man finne informasjon om hvordan man regner det ut, samt en tabell i bunnen som viser en rekke desibelverdier med korresponderende amplituder: <https://www.rapidtables.com/electric/decibel.html>.

## Polarisering

Polariseringen til signalene kan påvirke hvordan de takler atmosfæriske forhold. RHCP-signaler, altså signaler med “Right Hand Circular Polarization” brukes ofte i sammenheng med sending av signaler. En fordel med sirkulær polarisering er at man ikke får signaltap pga ulik polarisering av signalene. I tillegg er det slik at når et RHCP-signal treffer en flate, vil det sendes tilbake som et LHCP (Left Hand Circular Polarization) signal. Fordelen med dette er at RHCP-antenner vil ha mindre interferens av reflekterte bølger, altså LHCP-signaler som blandes inn i RHCP-signalene. (Antenna theory, u.å.)

## Frekvensområde og frekvensvalg

Båndbredden til signalet sier noe om frekvensspekteret til signalet. Et signal som sendes mellom 40 og 60 MHz vil da ha en båndbredde på 20MHz. Noen frekvensbånd har større båndbredde enn andre. I dette prosjektet er det mest relevant med frekvensbåndene VHF (Very High Frequency) og UHF (Ultra High Frequency). VHF har da et frekvensspekter på mellom 30 og 300MHz, mens UHF har et frekvensspekter på mellom 300-3000MHz. I dette prosjekter ser man satellittene holder seg på frekvenser rundt 137MHz og 1,7GHz, så det er disse to frekvensbåndene som er mest relevante. (Antenna theory, u.å.)

## SNR

SNR står for “Signal-to-Noise-Ratio” og er et tallet som forteller deg hvor sterkt det ønskede signalet er i forhold til det uønskede støyet er i signalet. Man ønsker helst at SNR-tallet er så høy som mulig. (Shure UK, 2016)

## EIRP

EIRP står for “Effective Isotropically Radiated Power”. Dette måles i desibel (dB). EIRP verdien forteller oss hva signalstyrken ville vært hvis antennen hadde utstrålt likt i alle retninger. Hvis EIRP ligger på 40dB så betyr det at det tilsvarer en uniform antenne som utstråler 40dB i alle retninger. (Sutron, u.å.)

## HRPT

HRPT står for “High Resolution Picture Transmission”. Hvis en satellitt har oppgitt en frekvens for dette, betyr det altså at man kan hente ned bilder i god oppløsning herfra.
MPT står for “Mission Picture Transmission”.
DPT står for “Delayed Picture Transmission”
APT står for “Automatic Picture Transmission” Det er lettere å hente ned bilder via denne kontra HRPT på grunn av mange ulike faktorer.
(Mdkenny, 2017)

<br>

### Referanser

- Antenna theory (u.å.) Polarization - EM Waves and Antennas. Hentet fra <https://www.antenna-theory.com/basics/polarization.php>

- Antenna theory (u.å.) Frequency Bands. Hentet fra <https://www.antenna-theory.com/basics/freqBands.php>

- Shure UK (3.mars 2016) How External Antennas Improve Signal-to-Noise Ratio. Hentet fra <https://www.shure.com/en-US/performance-production/louder/external-antennas-improve-signal-noise-ratio>

- Sutron (u.å.) Uplink EIRP. Hentet fra <https://www.sutron.com/wp-content/uploads/2013/12/UPLINK_EIRP_Decibel.pdf>

- Mdkenny (18.nov 2018) Meteorological satellite frequencies. Hentet fra <http://mdkenny.customer.netspace.net.au/metsat_frequencies.html#FY-3>
