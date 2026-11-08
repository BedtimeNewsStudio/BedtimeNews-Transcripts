---
source_url: "https://link.springer.com/article/10.1186/s40623-023-01787-7"
captured_at: 2026-11-08T14:28:42Z
title: "New GEONET analysis strategy at GSI: daily coordinates of over 1300 GNSS CORS in Japan throughout the last quarter century | Earth, Planets and Space | Springer Nature Link"
tool: tavily
---

> **网页快照**：2026-11-08 14:28 UTC 抓取自 [原始页面](https://link.springer.com/article/10.1186/s40623-023-01787-7)（工具：tavily）。

# New GEONET analysis strategy at GSI: daily coordinates of over 1300 GNSS CORS in Japan throughout the last quarter century | Earth, Planets and Space | Springer Nature Link

Advertisement

![Advertisement](//pubads.g.doubleclick.net/gampad/ad?iu=/270604982/springerlink/40623/article&sz=728x90&pos=top&articleid=s40623-023-01787-7)
![Springer Nature Link](/oscar-static/images/darwin/header/img/logo-springer-nature-link-05805fde18.svg)

# New GEONET analysis strategy at GSI: daily coordinates of over 1300 GNSS CORS in Japan throughout the last quarter century

You have full access to this open access article

![](https://media.springernature.com/w72/springer-static/cover-hires/journal/40623?as=webp)

7463 Accesses

74 Citations

2 
Altmetric

[Explore all metrics](/article/10.1186/s40623-023-01787-7/metrics)

### Abstract

The station coordinates derived from GNSS (Global Navigation Satellite System) with a conventional static method underpin the study of Earth and planetary science and surveying and mapping. For the continuous provision of high-quality coordinates, it is mandatory to cope with the increasing deviation from the global standard reference frame and the launch of modern GPS (Global Positioning System) satellites. To provide coordinates agreed with ITRF2014 (International Terrestrial Reference Frame 2014) at several millimeters for GEONET (GNSS Earth Observation Network System) in Japan, we developed a new analysis strategy named F5 and assessed the reprocessed station coordinates from 1996. The major updates in F5 can be summarized as incorporating global network processing and enhancements in troposphere modeling. As for the troposphere enhancements, a modern mapping function VMF1 (Vienna Mapping Functions 1) was employed and time intervals for troposphere estimates were shortened. Station coordinates in the global network showed a great agreement with ITRF2014 at several millimeters in the recent 20 years and comparable or slightly better performance with IGS (International GNSS Services) Analysis Centers. The RMS (root mean square) averaged over all GEONET stations indicated very high accuracy of 3.2 mm (horizontal) and 7.3 mm (vertical); the latter accounts for an improvement of roughly 10% from the previous strategy. Sensitivity tests about troposphere estimates revealed that the reduced RMS was completely due to the short time intervals, not the use of VMF1, which contributed to partly suppressing the spurious vertical annual deformation. These results confirm that F5 is sufficiently accurate for the requirements of individual applications and infer the capability of detecting smaller signals the previous strategy could not resolve.

### Graphical Abstract

![](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Figa_HTML.png)

### Explore related subjects

## Introduction

Since 1996, the Geospatial Information Authority of Japan (GSI) has operated a dense GNSS (Global Navigation Satellite System) CORS (Continuously Operating Reference Stations) network system, known as GEONET (GNSS Earth Observation Network System), which was initially established to understand the process of strain accumulation and release across Japan (e.g., Sagiya [2004](/article/10.1186/s40623-023-01787-7#ref-CR52 "Sagiya T (2004) A decade of GEONET: 1994–2003 The continuous GPS observation in Japan and its impact on earthquake studies. Earth Planets Space 56(8):xxix–xli"); Tsuji and Hatanaka [2018](/article/10.1186/s40623-023-01787-7#ref-CR58 "Tsuji H, Hatanaka Y (2018) GEONET as infrastructure for disaster mitigation. J Disaster Res 13(3):424–432")). The observation data and their daily coordinates are publicly provided and widely used to maintain the basis of surveying and mapping. The current system consists of over 1300 CORS with an average spacing of 20 km (Fig. [1](/article/10.1186/s40623-023-01787-7#Fig1)).

![Fig. 1](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig1_HTML.png)

GEONET station distribution. The bathymetric map was taken from ETOPO1 (NOAA National Geophysical Data Center [2009](/article/10.1186/s40623-023-01787-7#ref-CR40 "NOAA National Geophysical Data Center (2009) ETOPO1 1 Arc-Minute Global Relief Model. NOAA National Centers for Environmental Information. Accessed 14th October 2021"); Amante and Eakins [2009](/article/10.1186/s40623-023-01787-7#ref-CR3 "Amante C, Eakins BW (2009) ETOPO1 arc-minute global relief model: procedures, data sources and analysis. NOAA Technical Memorandum NESDIS NGDC-24 1-19"))

The daily coordinates of each station provide dense and continuous information about the complicated deformation field of Japan (e.g., Sagiya et al [2000](/article/10.1186/s40623-023-01787-7#ref-CR53 "Sagiya T, Miyazaki S, Tada T (2000) Continuous GPS array and present-day crustal deformation of Japan. Pure Appl Geophys 157(11):2303–2322"); Hatanaka et al. [2003](/article/10.1186/s40623-023-01787-7#ref-CR18 "Hatanaka Y, Iizuka T, Sawada M, Yamagiwa A, Kikuta Y, Johnson JM, Rocken C (2003) Improvement of the analysis strategy of GEONET. Bull Geogr Survey Inst 49:11–37")). Many challenges concerning geodesy and seismology have been resolved using the daily coordinates. These include understanding the crustal response of the loading effect by snow (Heki [2001](/article/10.1186/s40623-023-01787-7#ref-CR19 "Heki K (2001) Seasonal modulation of interseismic strain buildup in northeastern Japan driven by snow loads. Science 293(5527):89–92")) and heavy rainfall (Heki and Arief [2022](/article/10.1186/s40623-023-01787-7#ref-CR20 "Heki K, Arief S (2022) Crustal response to heavy rains in Southwest Japan 2017–2020. Earth Planet Sci Lett 578:117325"); Zhan et al. [2021](/article/10.1186/s40623-023-01787-7#ref-CR62 "Zhan W, Heki K, Arief S, Yoshida M (2021) Topographic amplification of crustal subsidence by the rainwater load of the 2019 typhoon Hagibis in Japan. J Geophys Res Solid Earth. 
                  https://doi.org/10.1029/2021JB021845
                  
                ")), identifying a rapidly deformed area by the secular plate motion, which is represented by Niigata–Kobe Tectonic Zone (Sagiya et al. [2000](/article/10.1186/s40623-023-01787-7#ref-CR53 "Sagiya T, Miyazaki S, Tada T (2000) Continuous GPS array and present-day crustal deformation of Japan. Pure Appl Geophys 157(11):2303–2322")), comprehending the source process of the 2011 gigantic earthquake off the coast of Tohoku region (Ozawa et al. [2011](/article/10.1186/s40623-023-01787-7#ref-CR43 "Ozawa S, Nishimura T, Suito H, Kobayashi T, Tobita M, Imakiire T (2011) Coseismic and postseismic slip of the 2011 magnitude-9 Tohoku-Oki earthquake. Nature 475(7356):373–376"); Suito [2017](/article/10.1186/s40623-023-01787-7#ref-CR56 "Suito H (2017) Importance of rheological heterogeneity for interpreting viscoelastic relaxation caused by the 2011 Tohoku-Oki earthquake. Earth Planet Space 69(1):1–12")), and detecting slow slip events along subduction zones, such as Nankai trough (Kano and Kato [2020](/article/10.1186/s40623-023-01787-7#ref-CR25 "Kano M, Kato A (2020) Detailed spatial slip distribution for short-term slow slip events along the Nankai subduction zone, southwest Japan. J Geophys Res Solid Earth 125(7):e2020JB019613. 
                  https://doi.org/10.1029/2020JB019613
                  
                ")) and Ryukyu trench (Nishimura [2014](/article/10.1186/s40623-023-01787-7#ref-CR39 "Nishimura T (2014) Short-term slow slip events along the Ryukyu Trench, southwestern Japan, observed by continuous GNSS. Prog Earth Planet Sci 1(1):1–13")). Regarding surveying and mapping, the daily coordinates have been used for semi-dynamic correction since 2010, which involves aligning positions at a current epoch obtained by GNSS to the map that is based on the survey at a reference epoch (Hiyama et al. [2010](/article/10.1186/s40623-023-01787-7#ref-CR21 "Hiyama Y, Morishita Y, Yamao H, Yutsudo T, Ochi K, Iwata M (2010) Towards the introduction of semi-dynamic correction. J GSI 120:55–61 (in Japanese)")). Such geospatial information management helps support social and economic activities. Furthermore, recent applications have included use as the fundamental data for the Centimeter-Level Augmentation Service (Cabinet Office [2022](/article/10.1186/s40623-023-01787-7#ref-CR7 "Cabinet Office (2022) Quasi-Zenith Satellite System Interface Specification Centimeter Level Augmentation Service (IS-QZSS-L6-005). 
                  https://qzss.go.jp/technical/download/ps-is-qzss.html
                  
                . Accessed 29 Jan 2023")), which precisely measures the positions of GNSS receivers in real time without the use of a reference station.

In other countries or regions, several efforts have been made to provide coordinates for a regionally densified CORS network. Each of these has its own inherent set of strengths and weaknesses. The location of 330 multi-GNSS stations in Europe, named EUREF (the Regional Reference Frame Sub-commission for Europe) Permanent Network (EPN; Bruyninx et al. [2019](/article/10.1186/s40623-023-01787-7#ref-CR6 "Bruyninx C, Legrand J, Fabian A, Pottiaux E (2019) GNSS metadata and data validation in the EUREF Permanent Network. GPS Solut 23(4):1–14")), is determined in the way that normal equations for the subnetworks are combined and solved with a minimum constraint condition imposed (Guidelines for the EPN Analysis Centres). In this approach, errors in the coordinates of stations considered in the minimum constraint do neither distort the network geometry nor significantly degrade the datum definition (Dach et al. [2015](/article/10.1186/s40623-023-01787-7#ref-CR9 "Dach R, Lutz S, Walser P, Fridez P (2015) Bernese GNSS Software Version 5.2. User manual. Astronomical Institute, University of Bern, Bern Open Publishing. 
                  https://boris.unibe.ch/72297
                  
                ")). However, the resultant reference frame is highly dependent on the choices of considered stations (Legrand and Bruyninx [2009](/article/10.1186/s40623-023-01787-7#ref-CR27 "Legrand J, Bruyninx C (2009) EPN reference frame alignment: consistency of the station positions. Bull Geodesy Geomatics 68(1):19–34")). Meanwhile, some recent works highlighted the application of PPP (Precise Point Positioning) for regional network processing (e.g., Ebner and Featherstone [2008](/article/10.1186/s40623-023-01787-7#ref-CR11 "Ebner R, Featherstone W (2008) How well can online GPS PPP post-processing services be used to establish geodetic survey control networks? J Appl Geodesy 2(3):149–157"); Grinter and Janssen [2012](/article/10.1186/s40623-023-01787-7#ref-CR17 "Grinter T, Janssen V (2012) Post-processed precise point positioning: a viable alternative? Proceedings of the 17th Association of Public Authority Surveyors Conference (APAS2012) Wollongong, New South Wales, Australia, 19–21 March 83–92.")). The PPP approach is superior to the differential one in that only a single receiver is necessary (Rizos et al. [2012](/article/10.1186/s40623-023-01787-7#ref-CR50 "Rizos, C., Janssen, V., Roberts, C. and Grinter, T. (2012) Precise Point Positioning: Is the era of differential GNSS positioning drawing to an end? In Proceedings of FIG Working Week 2012.")), which enables to simplify the operation of routine analysis. However, long convergence times are necessary for the ambiguity float solution to ensure the sufficient accuracy individual utilization requires (Seepersad [2012](/article/10.1186/s40623-023-01787-7#ref-CR54 "Seepersad GG (2012) Reduction of initial convergence period in GPS PPP data processing. MSc dissertation, York University, Toronto"); Grinter and Janssen [2012](/article/10.1186/s40623-023-01787-7#ref-CR17 "Grinter T, Janssen V (2012) Post-processed precise point positioning: a viable alternative? Proceedings of the 17th Association of Public Authority Surveyors Conference (APAS2012) Wollongong, New South Wales, Australia, 19–21 March 83–92.")). Furthermore, it is mandatory to fully understand the implications of transforming between a global and a regional datum (Rizos et al. [2012](/article/10.1186/s40623-023-01787-7#ref-CR50 "Rizos, C., Janssen, V., Roberts, C. and Grinter, T. (2012) Precise Point Positioning: Is the era of differential GNSS positioning drawing to an end? In Proceedings of FIG Working Week 2012.")).

Our previous analysis strategy “F3” needed to be updated owing to two reasons. The first was increasing deviation from the recent ITRF (International Terrestrial Reference Frame). F3 was based on the differential approach where a single reference station was fixed. There was a disadvantage that a common mode error appeared in the same direction and quantity at all of the GEONET stations due to the single fixing of mismodeled coordinates in the reference station. The coordinate at the reference station was determined under the regional network that covers East Asia and Oceania around Japan. The stations in the regional network have experienced either real or apparent shifts in their coordinates owing to earthquakes and equipment replacements since the end of IGS05 (Ferland [2006](/article/10.1186/s40623-023-01787-7#ref-CR14 "Ferland R (2006) [IGSMAIL-5447]: Proposed IGS05 Realization. 
                  https://lists.igs.org/pipermail/igsmail/2006/006818.html
                  
                . Accessed 29 Jan 2023")), i.e., the GNSS realization of ITRF2005 (Altamimi et al. [2007](/article/10.1186/s40623-023-01787-7#ref-CR1 "Altamimi Z, Collilieux X, Legrand J, Garayt B, Boucher C (2007) ITRF2005: a new release of the International Terrestrial Reference Frame based on time series of station positions and Earth Orientation Parameters. J Geophys Res Solid Earth 112:B09401. 
                  https://doi.org/10.1029/2007JB004949
                  
                ")) where F3 was aligned. Namely, the post-seismic deformation associated with the 2011 Tohoku-oki earthquake even affected Northeastern China (Meng et al. [2019](/article/10.1186/s40623-023-01787-7#ref-CR33 "Meng G, Su X, Wu W, Nikolay S, Takahashi H, Ohzono M, Gerasimenko M (2019) Crustal deformation of northeastern China following the 2011 Mw 9.0 Tohoku, Japan earthquake estimated from GPS observations: strain heterogeneity and seismicity. Remote Sens 11(24):3029")), and most of the antennas at the IGS (International GNSS Services) stations used for F3 have been replaced. As a result, the internal consistency within the network was no longer assured, and an increasing deviation from the recent ITRF had been observed particularly in the last decade.

The second reason was a forthcoming deterioration in accuracy. Bernese GNSS Software Version 5.0 (Dach et al. [2007](/article/10.1186/s40623-023-01787-7#ref-CR8 "Dach R, Hugentobler U, Fridez P, Meindl M (2007) User manual of the Bernese GPS software version 5.0. Astronomical Institute, University of Bern, 612")) was used for F3 but it cannot process GPS (Global Positioning System) Block III satellites, which were thus excluded from the process of estimating the station coordinates. Currently, the absence of Block III has little influence on the derived coordinates; however, the forthcoming replacement with Block III/IIIF is expected to considerably degrade the accuracy in the future.

In this paper, we present details of our new analysis strategy of GEONET “F5” that overcome the problems found in F3 and achieve the mm-level repeatability and consistency with the ITRF. First, we provide an overview of our analysis strategies. Then, we describe the basic concept of the F5 processing scheme, which comprises two steps: reference station analysis (RSA) and GEONET station analysis (GSA). Next, we describe the specifications of each analysis. After that, we then assess the performance of F5 throughout the last quarter century in terms of station coordinates. Finally, we discuss the future prospects of our analysis strategies.

## Overview of analysis strategies

In response to the deployment of GEONET in 1996, we started the routine analysis that continuously provides the coordinates of each station each day until the present. We previously updated the analysis strategy three times (Hatanaka et al. [2003](/article/10.1186/s40623-023-01787-7#ref-CR18 "Hatanaka Y, Iizuka T, Sawada M, Yamagiwa A, Kikuta Y, Johnson JM, Rocken C (2003) Improvement of the analysis strategy of GEONET. Bull Geogr Survey Inst 49:11–37"); Geodetic Observation Center [2004](/article/10.1186/s40623-023-01787-7#ref-CR15 "Griffiths J (2004) Special Issue: establishment of the nationwide observation system of 1200 GPS-based control stations. J GSI 103:1–51"); Nakagawa et al. [2009](/article/10.1186/s40623-023-01787-7#ref-CR37 "Nakagawa H, Toyofuku T, Kotani K, Miyahara B, Iwashita C, Kawamoto S, Hatanaka Y, Munekane H, Ishimoto M, Yutsudo T, Ishikura N, Sugawara Y (2009) Development and validation of GEONET new analysis strategy (Version 4). J GSI 118:1–8 (in Japanese)")), and we reprocessed data from 1996 each time to generate station coordinates over the entire period in a consistent manner. In April 2021, we developed a new analysis strategy F5 and released the reprocessed products. Subsequent results are routinely appended by the automatic analysis. Anyone can access two types of products: F5 and R5. These depend on the final and rapid IGS products: satellite ephemeris and earth orientation parameter (EOP; Table [1](/article/10.1186/s40623-023-01787-7#Tab1)). In addition, Q5, where IGS ultra-rapid products are applied, is available only for use within the government to rapidly grasp the crustal deformation field after an earthquake or volcanic eruption.

## Basic concept of processing scheme

The series of our analysis strategies consists of two steps: the reference station analysis (RSA) and the GEONET station analysis (GSA). RSA offers the ITRF-aligned coordinates of three GEONET stations: “Tsukuba-1,” “Tsukuba-3,” and “TSKB” stations. GSA offers the regionally densified coordinates; the coordinates of all GEONET stations are estimated by fixing the coordinate at one of the three stations derived from RSA. Unless the station is under maintenance, Tsukuba-1 is usually selected as the reference station.

In the RSA + GSA approach, errors in the coordinates of the reference station can propagate to all other GEONET stations as a common mode error. Nonetheless, we chose this approach in F5 because the two independent analyses simplify the troubleshooting of accuracy degradation due to the different noise characteristics in the coordinates. In addition, the regional network geometry is never distorted under the single fixing of the reference station.

To mitigate the common mode error and thus achieve excellent agreement with ITRF, we developed a new RSA scheme in which globally distributed IGS stations were used. Unlike the regional network of GSA, the global network of RSA has different noise characteristics due to longer baseline lengths and latitudes where stations locate. Therefore, a different set of parameters (e.g., threshold for quality checking, troposphere parameters) is adopted for each processing.

## Specification of F5 analysis strategy

### Reference station analysis (RSA)

The purpose of F5 RSA is to obtain the coordinates of the reference station for GSA that are aligned to ITRF2014. We use over 100 IGS stations that are globally distributed. For the reduced risk of abnormal solutions due to low-quality data, IGS stations with high-quality data are selected before the processing. The stations are selected according to the following steps. This procedure is applied once per year in the reprocessing term (1996 through 2020) and at recognizing a discrepancy of 1 cm (horizontal) or 2 cm (vertical) from ITRF2014 in the routine operation term (after 2021):

Choose IGb14 stations with an annual data acquisition rate above 70% (IGb14 is the revision of IGS14, which is the GNSS realization of ITRF2014; Rebischung and Schmid [2016](/article/10.1186/s40623-023-01787-7#ref-CR48 "Rebischung P, Schmid R (2016) IGS14/igs14.atx: a new framework for the IGS products. AGU fall meeting 2016"); Rebischung [2020](/article/10.1186/s40623-023-01787-7#ref-CR46 "Rebischung P (2020) [IGSMAIL-7921] Switch to IGb14 reference frame. 
                  https://lists.igs.org/pipermail/igsmail/2020/007917.html
                  
                . Accessed 29 Jan 2023")).

From the stations chosen in step 1, choose the IGS core sites that are used for IGb14. They have homogeneous spatial coverage on the Earth and thus are suitable for ensuring consistency with ITRF2014 (Rebischung and Schmid [2016](/article/10.1186/s40623-023-01787-7#ref-CR48 "Rebischung P, Schmid R (2016) IGS14/igs14.atx: a new framework for the IGS products. AGU fall meeting 2016")).

From stations not chosen in step 2, exclude stations with a large discrepancy between the IGS daily combined solution and the IGb14 model. First, the root mean square difference (RMSD) between the combined solution and the model is calculated for each station over the year. Then, the frequency at each bin of RMSD is calculated and fitted by a gamma distribution. Finally, stations with RMSD above the 99 percentile are excluded.

From stations on each face of a geodesic dome as defined in Fig. [2](/article/10.1186/s40623-023-01787-7#Fig2), select one station that maximizes the distance from stations chosen by step 2, and add it to the list of stations chosen in step 2. The geodesic dome is defined in advance of the station selection and consists of 42 pentagonal and hexagonal faces. The number of faces is suitable to rapidly add the station without disrupting the spatial coverage during the iteration of steps 2–4.

Repeat steps 2–4 until 130 stations are chosen for the Bernese version 5.2 to be capable of processing in F5 RSA.

![Fig. 2](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig2_HTML.png)

Distribution of stations used for F5 RSA in 2020 with a geodesic dome. The black lines indicate the baselines formed by the “SHORTEST” strategy in the Bernese software

For the further stabilization of the reference station coordinates, additional five GEONET stations registered to IGS (AIRA, CCJ2, ISHI, STK2, TSK2, and their historical monuments) are included without coordinate constraints. Once a station nearby the reference station is removed due to missing observation, discontinuity is likely to arise in coordinates at the reference station. To prevent this, well-maintained stations are distributed nearby the reference station (Fig. [2](/article/10.1186/s40623-023-01787-7#Fig2)).

The precise satellite orbit and EOP are given for the analysis. The IGS operational combined solutions are applied after February 14, 2015 whereas the repro2 solutions (Rebischung et al. [2016](/article/10.1186/s40623-023-01787-7#ref-CR49 "Rebischung P, Altamimi Z, Ray J, Garayt B (2016) The IGS contribution to ITRF2014. J Geodesy 90(7):611–630")) are applied before the day. The solutions before January 28, 2017 are transformed from the individual terrestrial reference frame into IGS14/IGb14 by applying the seven parameters of the Helmert transformation, which account for the origin shift, rotation, and scale shift between the pairs of reference frames, based on the method proposed by Hatanaka et al. ([2003](/article/10.1186/s40623-023-01787-7#ref-CR18 "Hatanaka Y, Iizuka T, Sawada M, Yamagiwa A, Kikuta Y, Johnson JM, Rocken C (2003) Improvement of the analysis strategy of GEONET. Bull Geogr Survey Inst 49:11–37")). The IGS antex (igs14\_wwww.
atx; Rebischung and Schmid [2016](/article/10.1186/s40623-023-01787-7#ref-CR48 "Rebischung P, Schmid R (2016) IGS14/igs14.atx: a new framework for the IGS products. AGU fall meeting 2016")) is used for the satellite and receiver antenna phase center calibration. The a priori coordinates of each constraining station are given by the IGb14 model, which represents the station coordinates at an arbitrary epoch with the combination of the station coordinates and velocity at the reference epoch and the post-seismic deformation by major earthquakes (Altamimi et al. [2016](/article/10.1186/s40623-023-01787-7#ref-CR2 "Altamimi Z, Rebischung P, Métivier L, Collilieux X (2016) ITRF2014: a new release of the International Terrestrial Reference Frame modeling nonlinear station motions. J Geophys Res Solid Earth 121(8):6109–6131"); Rebischung [2020](/article/10.1186/s40623-023-01787-7#ref-CR46 "Rebischung P (2020) [IGSMAIL-7921] Switch to IGb14 reference frame. 
                  https://lists.igs.org/pipermail/igsmail/2020/007917.html
                  
                . Accessed 29 Jan 2023")). The reference frame is realized by a minimum constraint condition. Typically, there are two ways of implementation: no-net-translation and no-net-rotation, which respectively impose the constraints of translation and rotation so that the entire system becomes zero. We carried out RSA analysis with the different minimum constraints to examine which one is more suitable for stabilizing the station coordinates (Additional file [1](/article/10.1186/s40623-023-01787-7#MOESM1): Text S1; Figure S1). No-net-translation largely stabilized, as the result, and thus we adopted it as a minimum constraint condition. ZTD (zenith tropospheric delay) and atmospheric gradient parameters are estimated every 1 and 24 h respectively. Global Mapping Function (Boehm et al. [2006b](/article/10.1186/s40623-023-01787-7#ref-CR5 "Boehm J, Niell A, Tregoning P, Schuh H (2006b) Global Mapping Function (GMF): a new empirical mapping function based on numerical weather model data. Geophys Res Lett 33:L07304. 
                  https://doi.org/10.1029/2005GL025546
                  
                ")) was employed for a mapping function. The other models and conventions used for RSA are listed in Table [2](/article/10.1186/s40623-023-01787-7#Tab2). Complete information is given at <ftp://terras.gsi.go.jp/data/coordinates_F5/DOC/GSI_F5FIX.acn>.

#### Processing flow in Bernese software

Preprocessing: Stations or satellites are excluded from the analysis if their quality indices retrieved by teqc (Estey and Meertens [1999](/article/10.1186/s40623-023-01787-7#ref-CR13 "Estey LH, Meertens CM (1999) TEQC: the multi-purpose toolkit for GPS/GLONASS data. GPS Solut 3(1):42–49")), a common GNSS preprocessing tool, do not satisfy the criteria listed in Table [3](/article/10.1186/s40623-023-01787-7#Tab3). Then, cycle slips are detected and corrected by the “MAUPRP,” the sub-program of the Bernese software.

Baseline forming: The “SHORTEST” strategy of the Bernese software is used to create a set of the shortest baselines. Figure [2](/article/10.1186/s40623-023-01787-7#Fig2) shows an example of the station distribution and baseline network.

Ambiguity resolution: Depending on the baseline length, different linear combinations are used for ambiguity resolution. The Melbourne–Wübbena combination (Wübbena [1985](/article/10.1186/s40623-023-01787-7#ref-CR60 "Wübbena G (1985) Software developments for geodetic positioning with GPS using TI 4100 code and carrier measurements. Proceedings of the first international symposium on precise positioning with the Global Positioning System 403–412."); Melbourne [1985](/article/10.1186/s40623-023-01787-7#ref-CR32 "Melbourne W (1985) THE CASE FOR RANGING IN GPS-BASED GEODETIC SYSTEMS. Proceedings of the first international symposium on precise positioning with the Global Positioning System 373–386")) and wide-lane combination are used for the long (> 200 km) and intermediate (20–200 km) baselines, respectively. After the wide-lane ambiguity resolution, the narrow-lane ambiguity is resolved by using the ionosphere-free linear combination. For the short baselines (< 20 km), basic L1 and L2 career phases are used.

Parameter estimation: The normal equation is solved to estimate the station coordinates in conjunction with troposphere parameters. The no-net-translation is imposed to estimate a set of coordinates aligned to ITRF2014.

### GEONET station analysis (GSA)

Similar to the previous strategy F3, we form three types of subnetworks called “backbone” (BB), “C,” and “A” clusters (Fig. [3](/article/10.1186/s40623-023-01787-7#Fig3)) considering the various observation periods and solve the normal equation for each subnetwork in a certain order. The number of GEONET stations has drastically increased from the end of the 1990s to the beginning of the 2000s. Some stations have been relocated during the recent 20 years and now there are around 1300 stations deployed. To cope with this and maintain the homogeneity of the solutions as much as possible over the entire period, the GEONET stations are divided into the following three types of clusters.

BB cluster: Approximately 20 stations are selected from the GEONET stations so that they are evenly distributed across the country. These stations should have been operated since GEONET was launched and should have particularly high-quality observing data. Then, we form a set of the shortest baseline network, namely the BB cluster (Fig. [3](/article/10.1186/s40623-023-01787-7#Fig3)i), and estimate the coordinates of these stations by fixing the reference coordinate derived by RSA. The troposphere parameters are simultaneously estimated with the station coordinates.

C cluster: We select just under 1000 stations, which consists of the C cluster, mostly constructed in the 1990s, including stations eventually relocated. Roughly 40 stations within 1000 stations are directly linked with BB stations by the “SHORTEST” strategy of Bernese software. Then, a set of radial networks are built by connecting the rest of the 1,000 stations with selected 40 stations and BB stations (Fig. [3](/article/10.1186/s40623-023-01787-7#Fig3)ii). The station coordinates and troposphere parameters are estimated according to the fixed parameters of the BB cluster.

A cluster: The remaining 300 stations newly constructed after the 2000s are called the A cluster. We form a set of radial networks in the same way as forming the C cluster (Fig. [3](/article/10.1186/s40623-023-01787-7#Fig3)iii) and estimate the station coordinates and troposphere parameters according to the fixed parameters of the center of networks.

![Fig. 3](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig3_HTML.png)

Network combination procedure. The yellow, dark blue, and light blue circles denote the GEONET stations. The star denotes the reference station. The red lines indicate the baselines spanning each cluster, while the gray lines are those defined in the previous steps

Through these steps, we use VMF1 (Vienna Mapping Functions 1; Boehm et al. [2006a](/article/10.1186/s40623-023-01787-7#ref-CR4 "Boehm J, Werl B, Schuh H (2006a) Troposphere mapping functions for GPS and very long baseline interferometry from European Centre for Medium-Range Weather Forecasts operational analysis data. J Geophys Res Solid Earth 111:B02406. 
                  https://doi.org/10.1029/2005JB003629
                  
                ")), which is newly supported by the Bernese Version 5.2. The use of NMF (Niell Mapping Function; Niell [1996](/article/10.1186/s40623-023-01787-7#ref-CR38 "Niell AE (1996) Global mapping functions for the atmosphere delay at radio wavelengths. J Geophys Res Solid Earth 101(B2):3227–3246. 
                  https://doi.org/10.1029/95JB03048
                  
                ")), an empirical mapping function used in F3, induces a latitude-dependent spurious annual deformation across Japan (Munekane et al. [2008](/article/10.1186/s40623-023-01787-7#ref-CR35 "Munekane H, Kuroishi Y, Hatanaka Y, Yarai H (2008) Spurious annual vertical deformations over Japan due to mismodelling of tropospheric delays. Geophys J Int 175(3):831–836")). This problem does not occur with the use of VMF1 owing to the direct calculation from the numerical weather prediction model with spatiotemporally high resolution (Munekane and Boehm [2010](/article/10.1186/s40623-023-01787-7#ref-CR34 "Munekane H, Boehm J (2010) Numerical simulation of troposphere-induced errors in GPS-derived geodetic time series over Japan. J Geodesy 84(7):405–417")). Moreover, troposphere parameters are estimated with shorter time intervals in F5 compared with F3. In F3, the time intervals of ZTD and gradient parameters are 3 and 24 h respectively. In F5, the intervals are 1 and 3 h, respectively.

The precise satellite orbit and EOP used for GSA are the same as those used for RSA. We created the phase center variations and offsets (PCVs and PCOs) for most stations ourselves to consider the influence of the original antennas, radomes, and monuments. For typical combinations of the equipment, the absolute PCVs and PCOs aligned to ITRF2014 were calculated using data observed at a pair of stations (Toyofuku et al. [2009](/article/10.1186/s40623-023-01787-7#ref-CR57 "Toyofuku T, Iwashita C, Hatanaka Y, Yutsudo T (2009) Development and evaluation of the antenna phase center models for GPS-based control stations. J GSI 118:9–15 (in Japanese)")). The PCVs and PCOs for other combinations, which accounted for a small proportion of GEONET stations, were created via conversion of the PCVs and PCOs for F3. This procedure is as follows; the differences in the PCV and PCO between IGS05 and IGS14 were calculated for the reference combination (i.e., AOA Dorne–Margolin T antenna without any radomes) and were added to the PCV and PCO that are aligned to IGS05. The a priori coordinates for the processing of GSA were given constant values because they had little influence on the final solution under very loose constraints. The models and conventions are listed in Table [4](/article/10.1186/s40623-023-01787-7#Tab4). Complete information is available at <ftp://terras.gsi.go.jp/data/coordinates_F5/DOC/GSI_F5.acn>.

#### Processing flow in Bernese software

The processing flow of the GSA procedure is as follows:

Preprocessing: same as RSA.

Baseline forming: create the BB, C, and A clusters as mentioned above.

Ambiguity resolution: Depending on the baseline length, different linear combinations are used. The Melbourne–Wübbena combination (Wübbena [1985](/article/10.1186/s40623-023-01787-7#ref-CR60 "Wübbena G (1985) Software developments for geodetic positioning with GPS using TI 4100 code and carrier measurements. Proceedings of the first international symposium on precise positioning with the Global Positioning System 403–412."); Melbourne [1985](/article/10.1186/s40623-023-01787-7#ref-CR32 "Melbourne W (1985) THE CASE FOR RANGING IN GPS-BASED GEODETIC SYSTEMS. Proceedings of the first international symposium on precise positioning with the Global Positioning System 373–386")) and wide-lane combination are used for long (> 100 km) and short (< 300 km) baselines, respectively. After the wide-lane ambiguity resolution in the two ways, the narrow-lane ambiguity is resolved by using the ionosphere-free linear combination.

Parameter estimation: The station coordinates are estimated in conjunction with the troposphere parameters in the order of the BB, C, and A clusters.

## Results and discussion

### Performance of RSA

#### Frame realization

The coordinates of the reference station must be consistent with ITRF2014 and stable because the subsequent GSA is processed by fixing the reference station. To assess the consistency between F5 RSA and ITRF2014, we compared F5 RSA solutions with daily solutions of IGS ACs (Analysis Centers) and their combination. Although Tsukuba-1 is usually selected as the reference station, we used TSKB, which is registered to IGS and thus exists in most ACs’ and IGS combined solutions. IGS operational solution was adopted from February 14, 2015 whereas the repro2 solution was used before the day. The specifications of the repro2 and operational solutions are summarized in Table [5](/article/10.1186/s40623-023-01787-7#Tab5). Station coordinates aligned to the original reference frame were converted into IGS14/IGb14 by application of the Helmert transformation between corresponding ITRF to ITRF2014. The station coordinates of F3 were also employed for comparison after the coordinate transformation to ITRF2014. For quantitative assessments, statistics of mean error (ME), standard deviation (STD), and root mean square error (RMSE) were also evaluated (Additional file [1](/article/10.1186/s40623-023-01787-7#MOESM1): Text S2 for the definition).

The time series of F5 showed good consistency with the IGS combined solution at several millimeters in the 2000s or later (Figs. [4](/article/10.1186/s40623-023-01787-7#Fig4), [5](/article/10.1186/s40623-023-01787-7#Fig5)). EMR, GRG, JPL, and MIT were more biased and scattered than F5. The large discrepancy of several centimeters found in the previous F3 solution was no longer observed in the new F5 solution (Fig. [5](/article/10.1186/s40623-023-01787-7#Fig5)). Furthermore, the degree and number of outliers, which were significant in F3 for the recent several years, were largely decreased. Both ME and STD demonstrated a mm-level consistency and repeatability in F5 after the 2000s (Table [6](/article/10.1186/s40623-023-01787-7#Tab6)a and b). They were slightly better than MIT and came close to COD. The RMSE for EW, NS, and UD components was 3.5, 4.0, and 7.2 mm in 2007–2009 and was 2.3, 2.0, and 4.6 mm in 2017–2019, respectively (Table [6](/article/10.1186/s40623-023-01787-7#Tab6)c). These statistics were also comparable to each AC, except for ULR.

![Fig. 4](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig4_HTML.png)

Station coordinate time series at **a** MAC1, **b** MAS1, **c** MATE, and **d** YELL with respect to the IGS combined solution. Their approximate positions are plotted in **e**. The 28-day moving average was plotted by the solid lines. The daily coordinates of F5 were also plotted by the dots. Each AC’s time series was drawn with a constant interval of 1 cm for clear visibility. ULR was eliminated because the temporal variation was too large to draw a consistent scale

![Fig. 5](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig5_HTML.png)

Same as Fig. [4](/article/10.1186/s40623-023-01787-7#Fig4), but at TSKB. The daily coordinates of F3 and their moving average were also plotted

These results suggest that the coordinates estimated by F5 RSA are successfully aligned to ITRF2014 with mm-level accuracy. However, COD, ESA, GFZ, and GTZ showed excellent consistency and repeatability, which were superior to F5. Among them, COD and ESA incorporated GLONASS (Global Navigation Satellite System) in addition to GPS, which likely contributed to the improved accuracy. Moreover, at the end of the repro2 period, COD, GFZ, and GTZ used roughly twice as many stations as F5 where up to 130 stations were integrated. This could have enriched the robustness against contamination of low quality data; thus, contributing to excellent consistency and repeatability. In the 1990s, however, F5 was more biased and scattered than after the 2000s. This is probably caused by selective availability, which is an intentional degradation of GPS signals applied before May 2000, and inhomogeneous station distribution in the processing network.

#### Noise characteristics

The spectral features were obtained to understand the noise characteristics of RSA. Figure [6](/article/10.1186/s40623-023-01787-7#Fig6) plotted the power spectrum in 365 days shifting the time window of half a year from 1996 to 2020 (See Additional file [1](/article/10.1186/s40623-023-01787-7#MOESM1): Text S2 for the detailed procedure). Each power spectrum was proportional to the inverse of frequency except for frequency-independent noise found at the highest frequency bands. These characteristics are consistent with past studies (Mao et al. [1999](/article/10.1186/s40623-023-01787-7#ref-CR30 "Mao A, Harrison CG, Dixon TH (1999) Noise in GPS coordinate time series. J Geophys Res Solid Earth 104(B2):2797–2816. 
                  https://doi.org/10.1029/1998JB900033
                  
                "); Williams et al. [2004](/article/10.1186/s40623-023-01787-7#ref-CR59 "Williams SD, Bock Y, Fang P, Jamason P, Nikolaidis RM, Prawirodirdjo L, Miller M, Johnson DJ (2004) Error analysis of continuous GPS position time series. J Geophys Res Solid Earth 109:B03412. 
                  https://doi.org/10.1029/2003JB002741
                  
                ")), which revealed that the noise hidden in station coordinates time series can be modeled by a combination of flicker noise and white noise when stations are globally distributed. The power spectrum after 2003 showed a relatively modest noise level than that before 2002; the noise level reduced to a quarter and a half for the horizontal and vertical components respectively. The possible reasons are the increased number of stations over 2003 and the discontinuation of selective availability.

![Fig. 6](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig6_HTML.png)

Power spectra for the station coordinates derived from F5 RSA. The power spectra in 365 days were stacked over the stations. The thin red and black lines indicate the individual spectrum in 1996 through 2003 and 2003 through 2020, respectively. The thick red and black lines indicate the stacked spectrum over 1996 through 2003 and 2003 through 2020, respectively. The dashed line in each panel indicates the gradient of the flicker noise as a reference

Figure [7](/article/10.1186/s40623-023-01787-7#Fig7) showed the F5 and ACs power spectrum stacked from 2003 through 2020, where the spectra in 365 days showed a modest noise level (See Additional file [1](/article/10.1186/s40623-023-01787-7#MOESM1): Text S2 for the detailed procedure). F5 showed a comparable or slightly better noise level among EMR, JPL, and MIT, which only use GPS. COD and ESA, which incorporate GLONASS (Global Navigation Satellite System) in addition to GPS, exhibited spectra with lower noise levels than those of the F5 and GPS-dependent ACs.

![Fig. 7](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig7_HTML.png)

Power spectra for the station coordinates derived from the individual processing. The power spectra in 365 days were stacked over the stations and period from 2003 to 2021 shifting an interval of half a year. Except for GRG and GTZ, the repro2 solution is used up to 2014. ULR was eliminated because the noise level was too high to draw a consistent scale. The blue hatched area indicates the fortnightly band. The pink hatched area indicates the period of 8 days and its second and third harmonics

F5 showed a spectral peak around 25.0–26.9 cpy (13.6–14.6 day) as well as most ACs spectrum (blue hatched bands in Fig. [7](/article/10.1186/s40623-023-01787-7#Fig7)). Because the Mf and Mf′ tides (i.e., a pair of long-term tides with periods of 13.66 and 13.63 days respectively) have a particularly substantial tide potential, their mismodeling directly imposes a spectral peak around the fortnightly band (Ray et al. [2013](/article/10.1186/s40623-023-01787-7#ref-CR45 "Ray J, Griffiths J, Collilieux X, Rebischung P (2013) Subseasonal GNSS positioning errors. Geophys Res Lett 40(22):5854–5860. 
                  https://doi.org/10.1002/2013GL058160
                  
                ")). In addition to the direct error, errors in sub-daily EOP tidal variations with periods close to 12 and 24 h are absorbed into the resonant GPS orbit and daily EOP parameter estimates, which resulted in aliased signals around the fortnightly band as well as GPS draconitic period for 24 h sampled processing (Penna and Stewart [2003](/article/10.1186/s40623-023-01787-7#ref-CR44 "Penna N, Stewart M (2003) Aliased tidal signatures in continuous GPS height time series. Geophys Res Lett 30(23):2184. 
                  https://doi.org/10.1029/2003GL018828
                  
                "); Griffiths and Ray [2013](/article/10.1186/s40623-023-01787-7#ref-CR16 "Griffiths J, Ray JR (2013) Sub-daily alias and draconitic errors in the IGS orbits. GPS Solutions 17(3):413–422")). M2 (12.42 h) and O1 (25.82 h) induce aliased signals at 14.76 and 14.19 days respectively (Penna and Stewart [2003](/article/10.1186/s40623-023-01787-7#ref-CR44 "Penna N, Stewart M (2003) Aliased tidal signatures in continuous GPS height time series. Geophys Res Lett 30(23):2184. 
                  https://doi.org/10.1029/2003GL018828
                  
                ")). As an exception, the JPL spectra did not show any peaks around this range, which can probably be attributed to the 30 h sampled processing (Ray et al. [2013](/article/10.1186/s40623-023-01787-7#ref-CR45 "Ray J, Griffiths J, Collilieux X, Rebischung P (2013) Subseasonal GNSS positioning errors. Geophys Res Lett 40(22):5854–5860. 
                  https://doi.org/10.1002/2013GL058160
                  
                ")).

COD and ESA exhibited a peak at 44.9–46.9 cpy (7.8–8.1 days) followed by weak signals at the second and third harmonics [90.8–92.8 cpy (3.9–4.0 days) and 134.7–138.7 cpy (2.6–2.7 days)] while those were absent in F5 and other ACs (pink hatched bands in Fig. [7](/article/10.1186/s40623-023-01787-7#Fig7)). Because the GLONASS tracking stations have a strongly non-uniform distribution, the orbit error with 8-day period (i.e., the ground repeat period) appears to have caused the periodic error in the station coordinates (Ray et al. [2013](/article/10.1186/s40623-023-01787-7#ref-CR45 "Ray J, Griffiths J, Collilieux X, Rebischung P (2013) Subseasonal GNSS positioning errors. Geophys Res Lett 40(22):5854–5860. 
                  https://doi.org/10.1002/2013GL058160
                  
                ")). The peak was also absent from the GFZ spectra because GLONASS data were not used for the repro2, which accounted for most of the stacking period.

### Performance of GSA

The accuracy in all GEONET stations in 2019 was assessed by RMS of the baseline vectors after removing the linear signal (See Additional file [1](/article/10.1186/s40623-023-01787-7#MOESM1): Text S3 for the definition). F5 showed latitude-dependent RMS of 1.5–2.5 mm (horizontal) and 6–8 mm (vertical), which increased toward the south (Fig. [8](/article/10.1186/s40623-023-01787-7#Fig8)a). The RMS averaged over the entire nation indicated 2.3 mm (EW) and 2.3 mm (NS), which correspond to 3.2 mm in the horizontal, and 7.3 mm in the vertical component. A similar spatial pattern was found in F3 (Fig. [8](/article/10.1186/s40623-023-01787-7#Fig8)b), but F5 showed a clear nationwide improvement in the UD component (Fig. [8](/article/10.1186/s40623-023-01787-7#Fig8)c). The averaged RMS in the UD component accounts for roughly 10% improvement (F5: 7.3 mm, F3: 7.9 mm), despite the deterioration in the southwestern islands of Japan.

![Fig. 8](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig8_HTML.png)

RMS of baseline vector in 2019 by **a** F5, **b** F3 and **c** their difference (F5 minus F3). The baseline vectors with respect to Ishioka were formed and the linear signal was removed in advance of each RMS calculation. The RMS values averaged over every station are listed at the top left on each panel

The latitude-dependent distribution of RMS would be relevant to the zenith wet delay, which is the wet part of ZTD and is responsible for large spatiotemporal variation (Leick et al. [2015](/article/10.1186/s40623-023-01787-7#ref-CR28 "Leick A, Repoport L, Tatarnikov D (2015) GPS satellite surveying, 4th edn. John Wiley & Sons")). In Japan, the spatiotemporal distribution of water vapor is highly variable in summer (Naito et al. [1998](/article/10.1186/s40623-023-01787-7#ref-CR36 "Naito I, Hatanaka Y, Mannoji Y, Ichikawa R, Shimada S, Yabuki T, Tsuji H, Tanaka T (1998) Global positioning system project to improve Japanese weather, earthquake predictions. EOS Trans AGU 79(26):301–311"); Iwabuchi et al. [2000](/article/10.1186/s40623-023-01787-7#ref-CR24 "Iwabuchi T, Naito I, Mannoji N (2000) A comparison of Global Positioning System retrieved precipitable water vapor with the numerical weather prediction analysis data over the Japanese Islands. J Geophys Res Atmos 105:4573–4585. 
                  https://doi.org/10.1029/1999JD901007
                  
                ")). As a matter of fact, the time series of the UD component at “Muroto-3” with respect to “Misumi” showed a large variance in summer (Fig. [9](/article/10.1186/s40623-023-01787-7#Fig9)). Meanwhile, the variance in summer was largely mitigated in F5. In the next subsection, we will further discuss how and to what extent the different troposphere estimates impact the spatiotemporal variation of the positioning accuracy.

![Fig. 9](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig9_HTML.png)

Change in the UD baseline vector at Muroto-3 with respect to Misumi. The deviation from the mean component is drawn. Each RMS value with respect to the mean component is listed at the top left of the figure

### Sensitivity of troposphere estimates

As for troposphere estimates of F5 GSA, we newly employed VMF1 and shortened time intervals. To distinguish each contribution, we conducted two extra analyses: the same setting as F3 but VMF1 was applied (F3VMF1) and the same as F3VMF1 but the time intervals for F5 were applied (F3VMF1\_SHORT).

Figure [10](/article/10.1186/s40623-023-01787-7#Fig10) plotted the RMS in the UD component by the individual solution and their difference (F3VMF1 minus F3 and F3VMF1\_SHORT minus F3VMF1). There was little difference in RMS between F3 and F3VMF1 (Fig. [10](/article/10.1186/s40623-023-01787-7#Fig10)d). In contrast, the difference between F3VMF1 and F3VMF1\_SHORT (Fig. [10](/article/10.1186/s40623-023-01787-7#Fig10)e) showed a highly correlated spatial pattern with the difference between F5 and F3 (Fig. [8](/article/10.1186/s40623-023-01787-7#Fig8)c). These results suggest that the reduced RMS in F5 was completely due to the shortening of time intervals, not the use of VMF1.

![Fig. 10](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig10_HTML.png)

Distribution of RMS for the UD component in **a** F3, **b** F3VMF1 and **c** F3VMF1\_SHORT and their difference (**d** F3VMF1 minus F3 and **e** F3VMF1\_SHORT minus F3VMF1)

We obtained the implication of high-frequent troposphere estimates based on the precipitable water vapor (PWV) retrieved from ZTD. We used the method proposed by Ohtani and Naito ([2000](/article/10.1186/s40623-023-01787-7#ref-CR42 "Ohtani R, Naito I (2000) Comparisons of GPS-derived precipitable water vapors with radiosonde observations in Japan. J Geophys Res Atmos 105(D22):26917–26929. 
                  https://doi.org/10.1029/2000JD900362
                  
                ")) for PWV retrieval. For its verification, surface specific humidity (SSH) provided by the Mesoscale Model in Japan Meteorological Agency (JMA; Ishida et al. [2022](/article/10.1186/s40623-023-01787-7#ref-CR23 "Ishida J, Aranami K, Kawano K, Matsubayashi K, Kitamura Y, Muroi C (2022) ASUCA: the JMA operational non-hydrostatic model. J Meteorol Soc Japan Ser II 100(5):825–846. 
                  https://doi.org/10.2151/jmsj.2022-043
                  
                ")) was used. Figure [11](/article/10.1186/s40623-023-01787-7#Fig11) indicated the temporal evolution of PWV and SSH at the “Shiojiri” station on July 24, 2019. In F3VMF1\_SHORT, PWV was maximum at 10 UTC (19JST) and then fell at the subsequent hour, which corresponds to the temporal changes reproduced by SSH (Fig. [11](/article/10.1186/s40623-023-01787-7#Fig11)). This can be expressed as the thermal-induced local circulation; sea breeze driven by the differing heat capacities on land and sea helped concentrate water vapor in the inland area, and then water vapor was released through intensive rainfall, which was indeed observed in the neighboring AMeDAS (Automated Meteorological Data Acquisition System) station after PWV reached its peak. By contrast, such a rapid time evolution was not tracked by F3VMF1; a broad and moderate change was observed over the day. Based on these results, it is clear that the troposphere estimates with the short time intervals improve the accuracy of station coordinates via the realistic tracking of the temporal evolution of water vapor.

![Fig. 11](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig11_HTML.png)

Changes in PWV and SSH at Shiojiri. The hourly precipitation observed at the nearest AMeDAS station, “Suwa,” is also drawn

In the southwestern islands of Japan, significant outliers were rarely observed in F3VMF1\_SHORT. On the day with the outlier, the temporal evolution of ZTD in F3VMF1\_SHORT showed an instantaneous rise across the archipelago around 15UTC while a gradual transition was observed in F3VMF1 (Additional file [1](/article/10.1186/s40623-023-01787-7#MOESM1): Figure S2). Based on the flat time series in SSH (Additional file [1](/article/10.1186/s40623-023-01787-7#MOESM1): Figure S3), this sharp rise would not be relevant to a meteorological signal, but instability of the parameter estimation. Because stations in the BB cluster were combined at first and solved by fixing Tsukuba-1, spatially heterogeneous noises were radially redistributed across Japan. Therefore, the noise in the cluster was imposed on the furthest station, which could invoke the outlier in the southwestern islands.

We introduced an index of coordinates difference between August and February (CDAF), which is the coordinate averaged over August with respect to that in February. This index is capable of capturing the spurious annual deformation in NMF because it contains phase lags of 220 degrees in an annual cosine curve (Munekane et al. [2008](/article/10.1186/s40623-023-01787-7#ref-CR35 "Munekane H, Kuroishi Y, Hatanaka Y, Yarai H (2008) Spurious annual vertical deformations over Japan due to mismodelling of tropospheric delays. Geophys J Int 175(3):831–836")), which corresponds to spurious subsidence in February and uplift in August. Figure [12](/article/10.1186/s40623-023-01787-7#Fig12) plotted of CDAF in the UD component by the individual solution and their difference (F3VMF1 minus F3 and F3VMF1\_SHORT minus F3VMF1). The CDAF varied from station to station (Fig. [12](/article/10.1186/s40623-023-01787-7#Fig12)a–c) because it involved not only spurious signals but also station-dependent crustal signals including co-/post-seismic deformation, SSE, and snow loading modulation. The ∆CDAF between F3 and F3VMF1 increased/decreased toward southwest/northeast from the reference station and was spatially correlated (Fig. [12](/article/10.1186/s40623-023-01787-7#Fig12)d). Meanwhile, the ∆CDAF between F3VMF1 and F3VMF1\_SHORT showed positive signatures in the entire domain and was spatially uncorrelated (Fig. [12](/article/10.1186/s40623-023-01787-7#Fig12)e).

![Fig. 12](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig12_HTML.png)

Same as Fig. [10](/article/10.1186/s40623-023-01787-7#Fig10), but for CDAF. Note that color scales in **d** and **e** are different

The past studies based on PPP analysis revealed that the spurious annual deformation reaches up to 3 mm half amplitude in the middle to high latitudes (Munekane et al. [2008](/article/10.1186/s40623-023-01787-7#ref-CR35 "Munekane H, Kuroishi Y, Hatanaka Y, Yarai H (2008) Spurious annual vertical deformations over Japan due to mismodelling of tropospheric delays. Geophys J Int 175(3):831–836")), and VMF1 contributes to mitigating the spurious signals (Munekane and Boehm [2010](/article/10.1186/s40623-023-01787-7#ref-CR34 "Munekane H, Boehm J (2010) Numerical simulation of troposphere-induced errors in GPS-derived geodetic time series over Japan. J Geodesy 84(7):405–417")). The decrease in ∆CDAF in the northern part of Japan was consistent with those studies but much less than 3 mm (6 mm in peak to peak). Instead, the ∆CDAF showed positive in the southwestern part of Japan (Fig. [12](/article/10.1186/s40623-023-01787-7#Fig12)d). The time series at Gusukube certainly illustrated that the use of VMF1 mitigated the spurious annual deformation in F3 (Fig. [13](/article/10.1186/s40623-023-01787-7#Fig13)). This discrepancy could be attributed to the nature of the network combination strategy in GSA. Under the single fixing of Tsukuba-1, spatially heterogeneous noises were radially redistributed within the whole network. As the result, the different noise characteristics between southwestern and northeastern Japan could be homogenized, which in turn mitigated the spurious movements in southwestern Japan. To confirm this hypothesis, a quantitative assessment of the error propagation is required.

![Fig. 13](//media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_Fig13_HTML.png)

Comparison of change in the UD baseline vector component at Gusukube with respect to Ishioka

## Future prospects

For further improvement on the accuracy, several issues are still open to discussion. Using multi-GNSS is one of them. As we have shown previously, COD and ESA, which incorporated GLONASS in addition to GPS, highlighted the smaller noise level than other GPS-dependent ACs and F5. This implies that the increasing number of satellites is capable of satisfying growing demands on positioning accuracy. In fact, the increased number of ACs has integrated GLONASS and Galileo as well as GPS and has contributed to constructing ITRF2020, the successor of ITRF2014 and the latest ITRF (Rebischung [2021](/article/10.1186/s40623-023-01787-7#ref-CR47 "Rebischung P (2021) [IGSMAIL-8044] Final IGS repro3 SINEX solutions available. 
                  https://lists.igs.org/pipermail/igsmail/2021/008040.html
                  
                . Accessed 29 Jan 2023")). Thus, processing with multi-GNSS constellations is important to improve the alignment to the ITRF successively updated in the future. The state-of-the-art modeling technique should be implemented in response to the update in IERS Conventions. For example, the IERS Conventions recommend applying higher-order ionosphere correction, modern ocean tidal loading models, and secular pole tide. Although the higher-order ionosphere correction was not taken into account in F5 RSA, it has diurnal, semiannual, and decadal signatures of several millimeters (Kedar et al. [2003](/article/10.1186/s40623-023-01787-7#ref-CR26 "Kedar S, Hajj GA, Wilson BD, Heflin MB (2003) The effect of the second order GPS ionospheric correction on receiver positions. Geophys Res Lett 30(16):1829. 
                  https://doi.org/10.1029/2003GL017639
                  
                ")). The implementation of minimum constraints condition is worth reconsidering as well. In COD, the geocenter motion parameter is introduced as an additional parameter and absorbs the detachment that ITRF in seasonal or shorter time scales is no longer the center of mass but the center of figure (Dong et al. [2003](/article/10.1186/s40623-023-01787-7#ref-CR10 "Dong D, Yunck T, Heflin M (2003) Origin of the international terrestrial reference frame. J Geophys Res Solid Earth 108(B4):2200. 
                  https://doi.org/10.1029/2002JB002035
                  
                "); Zajdel et al. [2019](/article/10.1186/s40623-023-01787-7#ref-CR61 "Zajdel R, Sośnica K, Dach R, Bury G, Prange L, Jäggi A (2019) Network effects and handling of the geocenter motion in multi-GNSS processing. J Geophys Res Solid Earth 124:5970–5989. 
                  https://doi.org/10.1029/2019JB017443
                  
                ")). However, ACs except for COD do not estimate the geocenter motion in repro2 and operational solutions. Further assessments are required for what type of parameters should be estimated in future strategies.

As a vital infrastructure for social and science communities, the daily coordinates in GEONET should have robustness as well as good accuracy. For this purpose, the use of QZSS (Quasi-Zenith Satellite System) is beneficial. As of 2022, four QZSS satellites are in commission and three more are planned to become available at the end of the 2023 fiscal year, which provides a preferable satellite constellation in the Asia-Oceania region. GEONET particularly embraces the benefit of the constellations due to the geographical location. Thus, further efforts for integrating QZSS are needed to achieve robust positioning as well as excellent accuracy.

## Conclusion

The daily station coordinates of over 1300 GEONET stations in Japan are routinely provided based on an analysis strategy. With the aim of alignment to ITRF2014 at several millimeters, we developed a new GNSS analysis strategy, named F5. Similar to the previous strategy F3, the RSA + GSA approach was employed. Namely, RSA provides the coordinate aligned to ITRF2014 at one of the GEONET stations, and GSA yields coordinates at all GEONET stations fixing the RSA-derived coordinate as a reference. To achieve excellent agreement with ITRF2014, we processed data of globally distributed IGS stations in RSA. The troposphere estimates were enhanced in terms of the application of the modern mapping function VMF1 and the shortening of time intervals.

Based on F5, we reprocessed the data from 1996 and assessed the obtained station coordinates. After the 2000s, the station coordinates in the global network were consistent with the IGS combined solution at several millimeters, which was comparable with IGS ACs’ performance. In TSKB, which is the candidate reference station in GSA, the RMSE with respect to IGS combined solution was 3.5 mm (EW), 4.0 mm (NS), and 7.2 mm (UD) in 2007–2009 and was 2.3 mm, 2.0 mm, and 4.6 mm in 2017–2019, respectively. In the 1990s, however, the station coordinates were biased and scattered. This was probably due to selective availability and the poor spatial coverage of the IGS-registered stations. The power spectra stacked over the entire network showed a noise level as small as other GPS-dependent ACs and depicted a common peak at the fortnightly band.

The coordinates at all GEONET stations indicated the RMS of 3.2 mm and 7.3 mm for the horizontal and vertical components respectively. In particular, the vertical component was improved by roughly 10% from F3. The sensitivity tests about the troposphere estimates revealed that this improvement is completely owing to the shortening in time intervals not the application of VMF1. The troposphere estimates with the short time intervals ensured us to successfully model the change in water vapor accompanied by a local atmospheric circulation system. The sensitivity tests also showed that the use of VMF1 mitigated the spurious annual vertical deformation to some extent. However, the spatial distribution of the mitigation was different compared with the past studies probably due to the nature of the single fixing.

These results confirmed that F5 has sufficient accuracy to support the study of Earth and planetary science and maintain the national geodetic datum. In addition, the performance of F5 suggested the capability of detecting smaller signals that were not resolved by the previous strategy. As a vital geodetic infrastructure, further efforts are needed to provide excellent accuracy and robust positioning.

## Availability of data and materials

Anyone lives in Japan can access our products and analysis strategy summary files after the user registration at <https://terras.gsi.go.jp/ftp_user_regist.php>. People in overseas are required to submit an application form that can be downloaded at <https://www.gsi.go.jp/ENGLISH/geonet_english.html>. The products available and those URL are as follows: station coordinates (routinely updated): <ftp://terras.gsi.go.jp/data/coordinates_F5/GPS>. <ftp://terras.gsi.go.jp/data/coordinates_R5/GPS>, troposphere parameters (routinely updated): <ftp://terras.gsi.go.jp/data/trp_F5/GPS>, analysis strategy summary for RSA: <ftp://terras.gsi.go.jp/data/coordinates_F5/DOC/GSI_F5FIX.acn>, and analysis strategy summary for GSA: <ftp://terras.gsi.go.jp/data/coordinates_F5/DOC/GSI_F5.acn>.

## Abbreviations

Analysis Center

Automated Meteorological Data Acquisition System

Backbone

Coordinates difference between August and February

Continuously operating reference stations

Earth orientation parameter

The Regional Reference Frame Sub-commission for Europe

EUREF permanent network

GNSS Earth Observation Network System

Global Navigation Satellite System

Global Navigation Satellite System

Global Positioning System

GEONET station analysis

Geospatial Information Authority of Japan

International GNSS service

International Terrestrial Reference Frame

Mean error

Niell Mapping Function

Precise Point Positioning

Root mean square difference

Root mean square error

Reference station analysis

Surface specific humidity

Standard deviation

Zenith tropospheric delay

Phase center variation

Phase center offset

Precipitable water vapor

Quasi-Zenith Satellite System

Vienna Mapping Functions 1

## References

Altamimi Z, Collilieux X, Legrand J, Garayt B, Boucher C (2007) ITRF2005: a new release of the International Terrestrial Reference Frame based on time series of station positions and Earth Orientation Parameters. J Geophys Res Solid Earth 112:B09401. <https://doi.org/10.1029/2007JB004949>

[Article](https://doi.org/10.1029%2F2007JB004949) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=ITRF2005%3A%20a%20new%20release%20of%20the%20International%20Terrestrial%20Reference%20Frame%20based%20on%20time%20series%20of%20station%20positions%20and%20Earth%20Orientation%20Parameters&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1029%2F2007JB004949&volume=112&publication_year=2007&author=Altamimi%2CZ&author=Collilieux%2CX&author=Legrand%2CJ&author=Garayt%2CB&author=Boucher%2CC)

Altamimi Z, Rebischung P, Métivier L, Collilieux X (2016) ITRF2014: a new release of the International Terrestrial Reference Frame modeling nonlinear station motions. J Geophys Res Solid Earth 121(8):6109–6131

[Article](https://doi.org/10.1002%2F2016JB013098) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=ITRF2014%3A%20a%20new%20release%20of%20the%20International%20Terrestrial%20Reference%20Frame%20modeling%20nonlinear%20station%20motions&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1002%2F2016JB013098&volume=121&issue=8&pages=6109-6131&publication_year=2016&author=Altamimi%2CZ&author=Rebischung%2CP&author=M%C3%A9tivier%2CL&author=Collilieux%2CX)

Amante C, Eakins BW (2009) ETOPO1 arc-minute global relief model: procedures, data sources and analysis. NOAA Technical Memorandum NESDIS NGDC-24 1-19

Boehm J, Werl B, Schuh H (2006a) Troposphere mapping functions for GPS and very long baseline interferometry from European Centre for Medium-Range Weather Forecasts operational analysis data. J Geophys Res Solid Earth 111:B02406. <https://doi.org/10.1029/2005JB003629>

[Article](https://doi.org/10.1029%2F2005JB003629) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Troposphere%20mapping%20functions%20for%20GPS%20and%20very%20long%20baseline%20interferometry%20from%20European%20Centre%20for%20Medium-Range%20Weather%20Forecasts%20operational%20analysis%20data&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1029%2F2005JB003629&volume=111&publication_year=2006&author=Boehm%2CJ&author=Werl%2CB&author=Schuh%2CH)

Boehm J, Niell A, Tregoning P, Schuh H (2006b) Global Mapping Function (GMF): a new empirical mapping function based on numerical weather model data. Geophys Res Lett 33:L07304. <https://doi.org/10.1029/2005GL025546>

[Article](https://doi.org/10.1029%2F2005GL025546) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Global%20Mapping%20Function%20%28GMF%29%3A%20a%20new%20empirical%20mapping%20function%20based%20on%20numerical%20weather%20model%20data&journal=Geophys%20Res%20Lett&doi=10.1029%2F2005GL025546&volume=33&publication_year=2006&author=Boehm%2CJ&author=Niell%2CA&author=Tregoning%2CP&author=Schuh%2CH)

Bruyninx C, Legrand J, Fabian A, Pottiaux E (2019) GNSS metadata and data validation in the EUREF Permanent Network. GPS Solut 23(4):1–14

[Article](https://link.springer.com/article/10.1007/s10291-019-0880-9) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=GNSS%20metadata%20and%20data%20validation%20in%20the%20EUREF%20Permanent%20Network&journal=GPS%20Solut&doi=10.1007%2Fs10291-019-0880-9&volume=23&issue=4&pages=1-14&publication_year=2019&author=Bruyninx%2CC&author=Legrand%2CJ&author=Fabian%2CA&author=Pottiaux%2CE)

Cabinet Office (2022) Quasi-Zenith Satellite System Interface Specification Centimeter Level Augmentation Service (IS-QZSS-L6-005). <https://qzss.go.jp/technical/download/ps-is-qzss.html>. Accessed 29 Jan 2023

Dach R, Hugentobler U, Fridez P, Meindl M (2007) User manual of the Bernese GPS software version 5.0. Astronomical Institute, University of Bern, 612

Dach R, Lutz S, Walser P, Fridez P (2015) Bernese GNSS Software Version 5.2. User manual. Astronomical Institute, University of Bern, Bern Open Publishing. <https://boris.unibe.ch/72297>

Dong D, Yunck T, Heflin M (2003) Origin of the international terrestrial reference frame. J Geophys Res Solid Earth 108(B4):2200. <https://doi.org/10.1029/2002JB002035>

[Article](https://doi.org/10.1029%2F2002JB002035) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Origin%20of%20the%20international%20terrestrial%20reference%20frame&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1029%2F2002JB002035&volume=108&issue=B4&publication_year=2003&author=Dong%2CD&author=Yunck%2CT&author=Heflin%2CM)

Ebner R, Featherstone W (2008) How well can online GPS PPP post-processing services be used to establish geodetic survey control networks? J Appl Geodesy 2(3):149–157

[Article](https://doi.org/10.1515%2FJAG.2008.017) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=How%20well%20can%20online%20GPS%20PPP%20post-processing%20services%20be%20used%20to%20establish%20geodetic%20survey%20control%20networks%3F&journal=J%20Appl%20Geodesy&doi=10.1515%2FJAG.2008.017&volume=2&issue=3&pages=149-157&publication_year=2008&author=Ebner%2CR&author=Featherstone%2CW)

Elson P, de Andrade E, Hattersley R, Campbell E, May R, Dawson A, et al. (2020) SciTools/cartopy: Cartopy 0.18.0. <https://zenodo.org/record/3783894>. Accessed 29 Jan 2023

Estey LH, Meertens CM (1999) TEQC: the multi-purpose toolkit for GPS/GLONASS data. GPS Solut 3(1):42–49

[Article](https://link.springer.com/article/10.1007/PL00012778) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=TEQC%3A%20the%20multi-purpose%20toolkit%20for%20GPS%2FGLONASS%20data&journal=GPS%20Solut&doi=10.1007%2FPL00012778&volume=3&issue=1&pages=42-49&publication_year=1999&author=Estey%2CLH&author=Meertens%2CCM)

Ferland R (2006) [IGSMAIL-5447]: Proposed IGS05 Realization. <https://lists.igs.org/pipermail/igsmail/2006/006818.html>. Accessed 29 Jan 2023

Griffiths J (2004) Special Issue: establishment of the nationwide observation system of 1200 GPS-based control stations. J GSI 103:1–51

[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Special%20Issue%3A%20establishment%20of%20the%20nationwide%20observation%20system%20of%201200%20GPS-based%20control%20stations&journal=J%20GSI&volume=103&pages=1-51&publication_year=2004&author=Griffiths%2CJ)

Griffiths J, Ray JR (2013) Sub-daily alias and draconitic errors in the IGS orbits. GPS Solutions 17(3):413–422

[Article](https://link.springer.com/article/10.1007/s10291-012-0289-1) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Sub-daily%20alias%20and%20draconitic%20errors%20in%20the%20IGS%20orbits&journal=GPS%20Solutions&doi=10.1007%2Fs10291-012-0289-1&volume=17&issue=3&pages=413-422&publication_year=2013&author=Griffiths%2CJ&author=Ray%2CJR)

Grinter T, Janssen V (2012) Post-processed precise point positioning: a viable alternative? Proceedings of the 17th Association of Public Authority Surveyors Conference (APAS2012) Wollongong, New South Wales, Australia, 19–21 March 83–92.

Hatanaka Y, Iizuka T, Sawada M, Yamagiwa A, Kikuta Y, Johnson JM, Rocken C (2003) Improvement of the analysis strategy of GEONET. Bull Geogr Survey Inst 49:11–37

[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Improvement%20of%20the%20analysis%20strategy%20of%20GEONET&journal=Bull%20Geogr%20Survey%20Inst&volume=49&pages=11-37&publication_year=2003&author=Hatanaka%2CY&author=Iizuka%2CT&author=Sawada%2CM&author=Yamagiwa%2CA&author=Kikuta%2CY&author=Johnson%2CJM&author=Rocken%2CC)

Heki K (2001) Seasonal modulation of interseismic strain buildup in northeastern Japan driven by snow loads. Science 293(5527):89–92

[Article](https://doi.org/10.1126%2Fscience.1061056) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Seasonal%20modulation%20of%20interseismic%20strain%20buildup%20in%20northeastern%20Japan%20driven%20by%20snow%20loads&journal=Science&doi=10.1126%2Fscience.1061056&volume=293&issue=5527&pages=89-92&publication_year=2001&author=Heki%2CK)

Heki K, Arief S (2022) Crustal response to heavy rains in Southwest Japan 2017–2020. Earth Planet Sci Lett 578:117325

[Article](https://doi.org/10.1016%2Fj.epsl.2021.117325) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Crustal%20response%20to%20heavy%20rains%20in%20Southwest%20Japan%202017%E2%80%932020&journal=Earth%20Planet%20Sci%20Lett&doi=10.1016%2Fj.epsl.2021.117325&volume=578&publication_year=2022&author=Heki%2CK&author=Arief%2CS)

Hiyama Y, Morishita Y, Yamao H, Yutsudo T, Ochi K, Iwata M (2010) Towards the introduction of semi-dynamic correction. J GSI 120:55–61 (**in Japanese**)

[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Towards%20the%20introduction%20of%20semi-dynamic%20correction&journal=J%20GSI&volume=120&pages=55-61&publication_year=2010&author=Hiyama%2CY&author=Morishita%2CY&author=Yamao%2CH&author=Yutsudo%2CT&author=Ochi%2CK&author=Iwata%2CM)

Hunter JD (2007) Matplotlib: a 2D graphics environment. Comput Sci Eng 9(3):90–95

[Article](https://doi.org/10.1109%2FMCSE.2007.55) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Matplotlib%3A%20a%202D%20graphics%20environment&journal=Comput%20Sci%20Eng&doi=10.1109%2FMCSE.2007.55&volume=9&issue=3&pages=90-95&publication_year=2007&author=Hunter%2CJD)

Ishida J, Aranami K, Kawano K, Matsubayashi K, Kitamura Y, Muroi C (2022) ASUCA: the JMA operational non-hydrostatic model. J Meteorol Soc Japan Ser II 100(5):825–846. <https://doi.org/10.2151/jmsj.2022-043>

[Article](https://doi.org/10.2151%2Fjmsj.2022-043) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=ASUCA%3A%20the%20JMA%20operational%20non-hydrostatic%20model&journal=J%20Meteorol%20Soc%20Japan%20Ser%20II&doi=10.2151%2Fjmsj.2022-043&volume=100&issue=5&pages=825-846&publication_year=2022&author=Ishida%2CJ&author=Aranami%2CK&author=Kawano%2CK&author=Matsubayashi%2CK&author=Kitamura%2CY&author=Muroi%2CC)

Iwabuchi T, Naito I, Mannoji N (2000) A comparison of Global Positioning System retrieved precipitable water vapor with the numerical weather prediction analysis data over the Japanese Islands. J Geophys Res Atmos 105:4573–4585. <https://doi.org/10.1029/1999JD901007>

[Article](https://doi.org/10.1029%2F1999JD901007) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=A%20comparison%20of%20Global%20Positioning%20System%20retrieved%20precipitable%20water%20vapor%20with%20the%20numerical%20weather%20prediction%20analysis%20data%20over%20the%20Japanese%20Islands&journal=J%20Geophys%20Res%20Atmos&doi=10.1029%2F1999JD901007&volume=105&pages=4573-4585&publication_year=2000&author=Iwabuchi%2CT&author=Naito%2CI&author=Mannoji%2CN)

Kano M, Kato A (2020) Detailed spatial slip distribution for short-term slow slip events along the Nankai subduction zone, southwest Japan. J Geophys Res Solid Earth 125(7):e2020JB019613. <https://doi.org/10.1029/2020JB019613>

[Article](https://doi.org/10.1029%2F2020JB019613) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Detailed%20spatial%20slip%20distribution%20for%20short-term%20slow%20slip%20events%20along%20the%20Nankai%20subduction%20zone%2C%20southwest%20Japan&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1029%2F2020JB019613&volume=125&issue=7&publication_year=2020&author=Kano%2CM&author=Kato%2CA)

Kedar S, Hajj GA, Wilson BD, Heflin MB (2003) The effect of the second order GPS ionospheric correction on receiver positions. Geophys Res Lett 30(16):1829. <https://doi.org/10.1029/2003GL017639>

[Article](https://doi.org/10.1029%2F2003GL017639) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=The%20effect%20of%20the%20second%20order%20GPS%20ionospheric%20correction%20on%20receiver%20positions&journal=Geophys%20Res%20Lett&doi=10.1029%2F2003GL017639&volume=30&issue=16&publication_year=2003&author=Kedar%2CS&author=Hajj%2CGA&author=Wilson%2CBD&author=Heflin%2CMB)

Legrand J, Bruyninx C (2009) EPN reference frame alignment: consistency of the station positions. Bull Geodesy Geomatics 68(1):19–34

[Google Scholar](http://scholar.google.com/scholar_lookup?&title=EPN%20reference%20frame%20alignment%3A%20consistency%20of%20the%20station%20positions&journal=Bull%20Geodesy%20Geomatics&volume=68&issue=1&pages=19-34&publication_year=2009&author=Legrand%2CJ&author=Bruyninx%2CC)

Leick A, Repoport L, Tatarnikov D (2015) GPS satellite surveying, 4th edn. John Wiley & Sons

[Google Scholar](http://scholar.google.com/scholar_lookup?&title=GPS%20satellite%20surveying&publication_year=2015&author=Leick%2CA&author=Repoport%2CL&author=Tatarnikov%2CD)

Lyard F, Lefevre F, Letellier T, Francis O (2006) Modelling the global ocean tides: modern insights from FES2004. Ocean Dyn 56:394–415

[Article](https://link.springer.com/article/10.1007/s10236-006-0086-x) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Modelling%20the%20global%20ocean%20tides%3A%20modern%20insights%20from%20FES2004&journal=Ocean%20Dyn&doi=10.1007%2Fs10236-006-0086-x&volume=56&pages=394-415&publication_year=2006&author=Lyard%2CF&author=Lefevre%2CF&author=Letellier%2CT&author=Francis%2CO)

Mao A, Harrison CG, Dixon TH (1999) Noise in GPS coordinate time series. J Geophys Res Solid Earth 104(B2):2797–2816. <https://doi.org/10.1029/1998JB900033>

[Article](https://doi.org/10.1029%2F1998JB900033) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Noise%20in%20GPS%20coordinate%20time%20series&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1029%2F1998JB900033&volume=104&issue=B2&pages=2797-2816&publication_year=1999&author=Mao%2CA&author=Harrison%2CCG&author=Dixon%2CTH)

Matsumoto K, Sato T, Takanezawa T, Ooe M (2001) GOTIC2: a program for computation of oceanic tidal loading effect. J Geodetic Soc Japan 47(1):243–248. <https://doi.org/10.11366/sokuchi1954.47.243>

[Article](https://doi.org/10.11366%2Fsokuchi1954.47.243) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=GOTIC2%3A%20a%20program%20for%20computation%20of%20oceanic%20tidal%20loading%20effect&journal=J%20Geodetic%20Soc%20Japan&doi=10.11366%2Fsokuchi1954.47.243&volume=47&issue=1&pages=243-248&publication_year=2001&author=Matsumoto%2CK&author=Sato%2CT&author=Takanezawa%2CT&author=Ooe%2CM)

Melbourne W (1985) THE CASE FOR RANGING IN GPS-BASED GEODETIC SYSTEMS. Proceedings of the first international symposium on precise positioning with the Global Positioning System 373–386

Meng G, Su X, Wu W, Nikolay S, Takahashi H, Ohzono M, Gerasimenko M (2019) Crustal deformation of northeastern China following the 2011 Mw 9.0 Tohoku, Japan earthquake estimated from GPS observations: strain heterogeneity and seismicity. Remote Sens 11(24):3029

[Article](https://doi.org/10.3390%2Frs11243029) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Crustal%20deformation%20of%20northeastern%20China%20following%20the%202011%20Mw%209.0%20Tohoku%2C%20Japan%20earthquake%20estimated%20from%20GPS%20observations%3A%20strain%20heterogeneity%20and%20seismicity&journal=Remote%20Sens&doi=10.3390%2Frs11243029&volume=11&issue=24&publication_year=2019&author=Meng%2CG&author=Su%2CX&author=Wu%2CW&author=Nikolay%2CS&author=Takahashi%2CH&author=Ohzono%2CM&author=Gerasimenko%2CM)

Munekane H, Boehm J (2010) Numerical simulation of troposphere-induced errors in GPS-derived geodetic time series over Japan. J Geodesy 84(7):405–417

[Article](https://link.springer.com/article/10.1007/s00190-010-0376-4) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Numerical%20simulation%20of%20troposphere-induced%20errors%20in%20GPS-derived%20geodetic%20time%20series%20over%20Japan&journal=J%20Geodesy&doi=10.1007%2Fs00190-010-0376-4&volume=84&issue=7&pages=405-417&publication_year=2010&author=Munekane%2CH&author=Boehm%2CJ)

Munekane H, Kuroishi Y, Hatanaka Y, Yarai H (2008) Spurious annual vertical deformations over Japan due to mismodelling of tropospheric delays. Geophys J Int 175(3):831–836

[Article](https://doi.org/10.1111%2Fj.1365-246X.2008.03980.x) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Spurious%20annual%20vertical%20deformations%20over%20Japan%20due%20to%20mismodelling%20of%20tropospheric%20delays&journal=Geophys%20J%20Int&doi=10.1111%2Fj.1365-246X.2008.03980.x&volume=175&issue=3&pages=831-836&publication_year=2008&author=Munekane%2CH&author=Kuroishi%2CY&author=Hatanaka%2CY&author=Yarai%2CH)

Naito I, Hatanaka Y, Mannoji Y, Ichikawa R, Shimada S, Yabuki T, Tsuji H, Tanaka T (1998) Global positioning system project to improve Japanese weather, earthquake predictions. EOS Trans AGU 79(26):301–311

[Article](https://doi.org/10.1029%2F98EO00222) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Global%20positioning%20system%20project%20to%20improve%20Japanese%20weather%2C%20earthquake%20predictions&journal=EOS%20Trans%20AGU&doi=10.1029%2F98EO00222&volume=79&issue=26&pages=301-311&publication_year=1998&author=Naito%2CI&author=Hatanaka%2CY&author=Mannoji%2CY&author=Ichikawa%2CR&author=Shimada%2CS&author=Yabuki%2CT&author=Tsuji%2CH&author=Tanaka%2CT)

Nakagawa H, Toyofuku T, Kotani K, Miyahara B, Iwashita C, Kawamoto S, Hatanaka Y, Munekane H, Ishimoto M, Yutsudo T, Ishikura N, Sugawara Y (2009) Development and validation of GEONET new analysis strategy (Version 4). J GSI 118:1–8 (**in Japanese**)

[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Development%20and%20validation%20of%20GEONET%20new%20analysis%20strategy%20%28Version%204%29&journal=J%20GSI&volume=118&pages=1-8&publication_year=2009&author=Nakagawa%2CH&author=Toyofuku%2CT&author=Kotani%2CK&author=Miyahara%2CB&author=Iwashita%2CC&author=Kawamoto%2CS&author=Hatanaka%2CY&author=Munekane%2CH&author=Ishimoto%2CM&author=Yutsudo%2CT&author=Ishikura%2CN&author=Sugawara%2CY)

Niell AE (1996) Global mapping functions for the atmosphere delay at radio wavelengths. J Geophys Res Solid Earth 101(B2):3227–3246. <https://doi.org/10.1029/95JB03048>

[Article](https://doi.org/10.1029%2F95JB03048) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Global%20mapping%20functions%20for%20the%20atmosphere%20delay%20at%20radio%20wavelengths&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1029%2F95JB03048&volume=101&issue=B2&pages=3227-3246&publication_year=1996&author=Niell%2CAE)

Nishimura T (2014) Short-term slow slip events along the Ryukyu Trench, southwestern Japan, observed by continuous GNSS. Prog Earth Planet Sci 1(1):1–13

[Article](https://link.springer.com/article/10.1186/s40645-014-0022-5) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Short-term%20slow%20slip%20events%20along%20the%20Ryukyu%20Trench%2C%20southwestern%20Japan%2C%20observed%20by%20continuous%20GNSS&journal=Prog%20Earth%20Planet%20Sci&doi=10.1186%2Fs40645-014-0022-5&volume=1&issue=1&pages=1-13&publication_year=2014&author=Nishimura%2CT)

NOAA National Geophysical Data Center (2009) ETOPO1 1 Arc-Minute Global Relief Model. NOAA National Centers for Environmental Information. Accessed 14th October 2021

Noll CE (2010) The Crustal Dynamics Data Information System: a resource to support scientific analysis using space geodesy. Adv Space Res 45(12):1421–1440

[Article](https://doi.org/10.1016%2Fj.asr.2010.01.018) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=The%20Crustal%20Dynamics%20Data%20Information%20System%3A%20a%20resource%20to%20support%20scientific%20analysis%20using%20space%20geodesy&journal=Adv%20Space%20Res&doi=10.1016%2Fj.asr.2010.01.018&volume=45&issue=12&pages=1421-1440&publication_year=2010&author=Noll%2CCE)

Ohtani R, Naito I (2000) Comparisons of GPS-derived precipitable water vapors with radiosonde observations in Japan. J Geophys Res Atmos 105(D22):26917–26929. <https://doi.org/10.1029/2000JD900362>

[Article](https://doi.org/10.1029%2F2000JD900362) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Comparisons%20of%20GPS-derived%20precipitable%20water%20vapors%20with%20radiosonde%20observations%20in%20Japan&journal=J%20Geophys%20Res%20Atmos&doi=10.1029%2F2000JD900362&volume=105&issue=D22&pages=26917-26929&publication_year=2000&author=Ohtani%2CR&author=Naito%2CI)

Ozawa S, Nishimura T, Suito H, Kobayashi T, Tobita M, Imakiire T (2011) Coseismic and postseismic slip of the 2011 magnitude-9 Tohoku-Oki earthquake. Nature 475(7356):373–376

[Article](https://doi.org/10.1038%2Fnature10227) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Coseismic%20and%20postseismic%20slip%20of%20the%202011%20magnitude-9%20Tohoku-Oki%20earthquake&journal=Nature&doi=10.1038%2Fnature10227&volume=475&issue=7356&pages=373-376&publication_year=2011&author=Ozawa%2CS&author=Nishimura%2CT&author=Suito%2CH&author=Kobayashi%2CT&author=Tobita%2CM&author=Imakiire%2CT)

Penna N, Stewart M (2003) Aliased tidal signatures in continuous GPS height time series. Geophys Res Lett 30(23):2184. <https://doi.org/10.1029/2003GL018828>

[Article](https://doi.org/10.1029%2F2003GL018828) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Aliased%20tidal%20signatures%20in%20continuous%20GPS%20height%20time%20series&journal=Geophys%20Res%20Lett&doi=10.1029%2F2003GL018828&volume=30&issue=23&publication_year=2003&author=Penna%2CN&author=Stewart%2CM)

Ray J, Griffiths J, Collilieux X, Rebischung P (2013) Subseasonal GNSS positioning errors. Geophys Res Lett 40(22):5854–5860. <https://doi.org/10.1002/2013GL058160>

[Article](https://doi.org/10.1002%2F2013GL058160) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Subseasonal%20GNSS%20positioning%20errors&journal=Geophys%20Res%20Lett&doi=10.1002%2F2013GL058160&volume=40&issue=22&pages=5854-5860&publication_year=2013&author=Ray%2CJ&author=Griffiths%2CJ&author=Collilieux%2CX&author=Rebischung%2CP)

Rebischung P (2020) [IGSMAIL-7921] Switch to IGb14 reference frame. <https://lists.igs.org/pipermail/igsmail/2020/007917.html>. Accessed 29 Jan 2023

Rebischung P (2021) [IGSMAIL-8044] Final IGS repro3 SINEX solutions available. <https://lists.igs.org/pipermail/igsmail/2021/008040.html>. Accessed 29 Jan 2023

Rebischung P, Schmid R (2016) IGS14/igs14.atx: a new framework for the IGS products. AGU fall meeting 2016

Rebischung P, Altamimi Z, Ray J, Garayt B (2016) The IGS contribution to ITRF2014. J Geodesy 90(7):611–630

[Article](https://link.springer.com/article/10.1007/s00190-016-0897-6) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=The%20IGS%20contribution%20to%20ITRF2014&journal=J%20Geodesy&doi=10.1007%2Fs00190-016-0897-6&volume=90&issue=7&pages=611-630&publication_year=2016&author=Rebischung%2CP&author=Altamimi%2CZ&author=Ray%2CJ&author=Garayt%2CB)

Rizos, C., Janssen, V., Roberts, C. and Grinter, T. (2012) Precise Point Positioning: Is the era of differential GNSS positioning drawing to an end? In Proceedings of FIG Working Week 2012.

Saastamoinen J (1973) Contributions to the theory of atmospheric refraction: Part II. Refraction corrections in satellite geodesy. Bull Géodésique 1946–1975(107):13–34

[Article](https://link.springer.com/article/10.1007/BF02522083) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Contributions%20to%20the%20theory%20of%20atmospheric%20refraction%3A%20Part%20II.%20Refraction%20corrections%20in%20satellite%20geodesy&journal=Bull%20G%C3%A9od%C3%A9sique&doi=10.1007%2FBF02522083&volume=1946%E2%80%931975&issue=107&pages=13-34&publication_year=1973&author=Saastamoinen%2CJ)

Sagiya T (2004) A decade of GEONET: 1994–2003 The continuous GPS observation in Japan and its impact on earthquake studies. Earth Planets Space 56(8):xxix–xli

[Article](https://link.springer.com/article/10.1186/BF03353077) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=A%20decade%20of%20GEONET%3A%201994%E2%80%932003%20The%20continuous%20GPS%20observation%20in%20Japan%20and%20its%20impact%20on%20earthquake%20studies&journal=Earth%20Planets%20Space&doi=10.1186%2FBF03353077&volume=56&issue=8&pages=xxix-xli&publication_year=2004&author=Sagiya%2CT)

Sagiya T, Miyazaki S, Tada T (2000) Continuous GPS array and present-day crustal deformation of Japan. Pure Appl Geophys 157(11):2303–2322

[Article](https://link.springer.com/article/10.1007/PL00022507) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Continuous%20GPS%20array%20and%20present-day%20crustal%20deformation%20of%20Japan&journal=Pure%20Appl%20Geophys&doi=10.1007%2FPL00022507&volume=157&issue=11&pages=2303-2322&publication_year=2000&author=Sagiya%2CT&author=Miyazaki%2CS&author=Tada%2CT)

Seepersad GG (2012) Reduction of initial convergence period in GPS PPP data processing. MSc dissertation, York University, Toronto

Steigenberger P, Rothacher M, Dietrich R, Fritsche M, Rülke A, Vey S (2006) Reprocessing of a global GPS network. J Geophys Res Solid Earth 111:B05402. <https://doi.org/10.1029/2005JB003747>

[Article](https://doi.org/10.1029%2F2005JB003747) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Reprocessing%20of%20a%20global%20GPS%20network&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1029%2F2005JB003747&volume=111&publication_year=2006&author=Steigenberger%2CP&author=Rothacher%2CM&author=Dietrich%2CR&author=Fritsche%2CM&author=R%C3%BClke%2CA&author=Vey%2CS)

Suito H (2017) Importance of rheological heterogeneity for interpreting viscoelastic relaxation caused by the 2011 Tohoku-Oki earthquake. Earth Planet Space 69(1):1–12

[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Importance%20of%20rheological%20heterogeneity%20for%20interpreting%20viscoelastic%20relaxation%20caused%20by%20the%202011%20Tohoku-Oki%20earthquake&journal=Earth%20Planet%20Space&volume=69&issue=1&pages=1-12&publication_year=2017&author=Suito%2CH)

Toyofuku T, Iwashita C, Hatanaka Y, Yutsudo T (2009) Development and evaluation of the antenna phase center models for GPS-based control stations. J GSI 118:9–15 (**in Japanese**)

[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Development%20and%20evaluation%20of%20the%20antenna%20phase%20center%20models%20for%20GPS-based%20control%20stations&journal=J%20GSI&volume=118&pages=9-15&publication_year=2009&author=Toyofuku%2CT&author=Iwashita%2CC&author=Hatanaka%2CY&author=Yutsudo%2CT)

Tsuji H, Hatanaka Y (2018) GEONET as infrastructure for disaster mitigation. J Disaster Res 13(3):424–432

[Article](https://doi.org/10.20965%2Fjdr.2018.p0424) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=GEONET%20as%20infrastructure%20for%20disaster%20mitigation&journal=J%20Disaster%20Res&doi=10.20965%2Fjdr.2018.p0424&volume=13&issue=3&pages=424-432&publication_year=2018&author=Tsuji%2CH&author=Hatanaka%2CY)

Williams SD, Bock Y, Fang P, Jamason P, Nikolaidis RM, Prawirodirdjo L, Miller M, Johnson DJ (2004) Error analysis of continuous GPS position time series. J Geophys Res Solid Earth 109:B03412. <https://doi.org/10.1029/2003JB002741>

[Article](https://doi.org/10.1029%2F2003JB002741) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Error%20analysis%20of%20continuous%20GPS%20position%20time%20series&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1029%2F2003JB002741&volume=109&publication_year=2004&author=Williams%2CSD&author=Bock%2CY&author=Fang%2CP&author=Jamason%2CP&author=Nikolaidis%2CRM&author=Prawirodirdjo%2CL&author=Miller%2CM&author=Johnson%2CDJ)

Wübbena G (1985) Software developments for geodetic positioning with GPS using TI 4100 code and carrier measurements. Proceedings of the first international symposium on precise positioning with the Global Positioning System 403–412.

Zajdel R, Sośnica K, Dach R, Bury G, Prange L, Jäggi A (2019) Network effects and handling of the geocenter motion in multi-GNSS processing. J Geophys Res Solid Earth 124:5970–5989. <https://doi.org/10.1029/2019JB017443>

[Article](https://doi.org/10.1029%2F2019JB017443) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Network%20effects%20and%20handling%20of%20the%20geocenter%20motion%20in%20multi-GNSS%20processing&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1029%2F2019JB017443&volume=124&pages=5970-5989&publication_year=2019&author=Zajdel%2CR&author=So%C5%9Bnica%2CK&author=Dach%2CR&author=Bury%2CG&author=Prange%2CL&author=J%C3%A4ggi%2CA)

Zhan W, Heki K, Arief S, Yoshida M (2021) Topographic amplification of crustal subsidence by the rainwater load of the 2019 typhoon Hagibis in Japan. J Geophys Res Solid Earth. <https://doi.org/10.1029/2021JB021845>

[Article](https://doi.org/10.1029%2F2021JB021845) 
[Google Scholar](http://scholar.google.com/scholar_lookup?&title=Topographic%20amplification%20of%20crustal%20subsidence%20by%20the%20rainwater%20load%20of%20the%202019%20typhoon%20Hagibis%20in%20Japan&journal=J%20Geophys%20Res%20Solid%20Earth&doi=10.1029%2F2021JB021845&publication_year=2021&author=Zhan%2CW&author=Heki%2CK&author=Arief%2CS&author=Yoshida%2CM)

[Download references](https://citation-needed.springer.com/v2/references/10.1186/s40623-023-01787-7?format=refman&flavour=references)

## Acknowledgements

The Bernese GNSS software version 5.2 (Dach et al., 2015) were used for the GNSS data analysis. The daily 30-second GNSS data, precise satellite orbit, and EOP were provided by the Crustal Dynamics Data Information System (Noll, 2010). The VMF1 data were acquired from VMF Data Server (<https://doi.org/10.17616/R3RD2H>). The Mesoscale Model data were provided by JMA and were acquired from the GPV archive site (<http://dias.tkl.iis.u-tokyo.ac.jp/gpv/>) managed by the Institute of Industrial Science, The University of Tokyo. The AMeDAS data were acquired from the JMA web site (<https://www.data.jma.go.jp/obd/stats/etrn/index.php>). Figures are drawn using matplotlib (Hunter, 2007) and Cartopy (Elson et al., 2020). The authors acknowledge all contributors for developing and deploying these data, products, and software. They thank the Basara Miyahara and Hiroshi Munekane as well as other GSI colleagues for advising us on technical matters. They also acknowledge the comments by three anonymous reviewers and the editor in improving the manuscript.

## Funding

This work was supported by the Geospatial Information Authority of Japan.

## Author information

### Authors and Affiliations

Geospatial Information Authority of Japan, 1 Kitasato, Tsukuba, Ibaraki, 305-0811, Japan

Naofumi Takamatsu, Hiroki Muramatsu, Satoshi Abe, Yuki Hatanaka, Tomoaki Furuya, Yasuaki Kakiage, Kazuyuki Ohashi, Chiaki Kato, Keitaro Ohno & Satoshi Kawamoto

Search author on:[PubMed](https://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&term=Naofumi%20Takamatsu) [Google Scholar](https://scholar.google.co.uk/scholar?as_q=&num=10&btnG=Search+Scholar&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=%22Naofumi%20Takamatsu%22&as_publication=&as_ylo=&as_yhi=&as_allsubj=all&hl=en)

Search author on:[PubMed](https://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&term=Hiroki%20Muramatsu) [Google Scholar](https://scholar.google.co.uk/scholar?as_q=&num=10&btnG=Search+Scholar&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=%22Hiroki%20Muramatsu%22&as_publication=&as_ylo=&as_yhi=&as_allsubj=all&hl=en)

Search author on:[PubMed](https://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&term=Satoshi%20Abe) [Google Scholar](https://scholar.google.co.uk/scholar?as_q=&num=10&btnG=Search+Scholar&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=%22Satoshi%20Abe%22&as_publication=&as_ylo=&as_yhi=&as_allsubj=all&hl=en)

Search author on:[PubMed](https://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&term=Yuki%20Hatanaka) [Google Scholar](https://scholar.google.co.uk/scholar?as_q=&num=10&btnG=Search+Scholar&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=%22Yuki%20Hatanaka%22&as_publication=&as_ylo=&as_yhi=&as_allsubj=all&hl=en)

Search author on:[PubMed](https://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&term=Tomoaki%20Furuya) [Google Scholar](https://scholar.google.co.uk/scholar?as_q=&num=10&btnG=Search+Scholar&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=%22Tomoaki%20Furuya%22&as_publication=&as_ylo=&as_yhi=&as_allsubj=all&hl=en)

Search author on:[PubMed](https://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&term=Yasuaki%20Kakiage) [Google Scholar](https://scholar.google.co.uk/scholar?as_q=&num=10&btnG=Search+Scholar&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=%22Yasuaki%20Kakiage%22&as_publication=&as_ylo=&as_yhi=&as_allsubj=all&hl=en)

Search author on:[PubMed](https://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&term=Kazuyuki%20Ohashi) [Google Scholar](https://scholar.google.co.uk/scholar?as_q=&num=10&btnG=Search+Scholar&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=%22Kazuyuki%20Ohashi%22&as_publication=&as_ylo=&as_yhi=&as_allsubj=all&hl=en)

Search author on:[PubMed](https://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&term=Chiaki%20Kato) [Google Scholar](https://scholar.google.co.uk/scholar?as_q=&num=10&btnG=Search+Scholar&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=%22Chiaki%20Kato%22&as_publication=&as_ylo=&as_yhi=&as_allsubj=all&hl=en)

Search author on:[PubMed](https://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&term=Keitaro%20Ohno) [Google Scholar](https://scholar.google.co.uk/scholar?as_q=&num=10&btnG=Search+Scholar&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=%22Keitaro%20Ohno%22&as_publication=&as_ylo=&as_yhi=&as_allsubj=all&hl=en)

Search author on:[PubMed](https://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=search&term=Satoshi%20Kawamoto) [Google Scholar](https://scholar.google.co.uk/scholar?as_q=&num=10&btnG=Search+Scholar&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=%22Satoshi%20Kawamoto%22&as_publication=&as_ylo=&as_yhi=&as_allsubj=all&hl=en)

### Contributions

NT performed a reprocessing and made an assessment for them. HM, SA, YK, and KOhn developed the prototype system of RSA. YH, Koha, and CK developed the prototype system of GSA. TF and SK organized and managed technical matters in this project. All the authors have read and approved the final manuscript.

### Corresponding author

Correspondence to
[Naofumi Takamatsu](mailto:takamatsu-n96rh@mlit.go.jp).

## Ethics declarations

### Ethics approval and consent to participate

Not applicable.

### Consent for publication

Not applicable.

### Competing interests

No competing interests.

## Additional information

### Publisher's Note

Springer Nature remains neutral with regard to jurisdictional claims in published maps and institutional affiliations.

## Supplementary Information

### [**Additional file 1:** (download DOCX )](https://static-content.springer.com/esm/art%3A10.1186%2Fs40623-023-01787-7/MediaObjects/40623_2023_1787_MOESM1_ESM.docx)

supplementary texts and figures.

## Rights and permissions

**Open Access** This article is licensed under a Creative Commons Attribution 4.0 International License, which permits use, sharing, adaptation, distribution and reproduction in any medium or format, as long as you give appropriate credit to the original author(s) and the source, provide a link to the Creative Commons licence, and indicate if changes were made. The images or other third party material in this article are included in the article's Creative Commons licence, unless indicated otherwise in a credit line to the material. If material is not included in the article's Creative Commons licence and your intended use is not permitted by statutory regulation or exceeds the permitted use, you will need to obtain permission directly from the copyright holder. To view a copy of this licence, visit <http://creativecommons.org/licenses/by/4.0/>.

[Reprints and permissions](https://s100.copyright.com/AppDispatchServlet?title=New%20GEONET%20analysis%20strategy%20at%20GSI%3A%20daily%20coordinates%20of%20over%201300%20GNSS%20CORS%20in%20Japan%20throughout%20the%20last%20quarter%20century&author=Naofumi%20Takamatsu%20et%20al&contentID=10.1186%2Fs40623-023-01787-7&copyright=The%20Author%28s%29&publication=1880-5981&publicationDate=2023-04-06&publisherName=SpringerNature&orderBeanReset=true&oa=CC%20BY)

## About this article

![Check for updates. Verify currency and authenticity via CrossMark](data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjgxIiB3aWR0aD0iNTciIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj48cGF0aCBkPSJtMTcuMzUgMzUuNDUgMjEuMy0xNC4ydi0xNy4wM2gtMjEuMyIgZmlsbD0iIzk4OTg5OCIvPjxwYXRoIGQ9Im0zOC42NSAzNS40NS0yMS4zLTE0LjJ2LTE3LjAzaDIxLjMiIGZpbGw9IiM3NDc0NzQiLz48cGF0aCBkPSJtMjggLjVjLTEyLjk4IDAtMjMuNSAxMC41Mi0yMy41IDIzLjVzMTAuNTIgMjMuNSAyMy41IDIzLjUgMjMuNS0xMC41MiAyMy41LTIzLjVjMC02LjIzLTIuNDgtMTIuMjEtNi44OC0xNi42Mi00LjQxLTQuNC0xMC4zOS02Ljg4LTE2LjYyLTYuODh6bTAgNDEuMjVjLTkuOCAwLTE3Ljc1LTcuOTUtMTcuNzUtMTcuNzVzNy45NS0xNy43NSAxNy43NS0xNy43NSAxNy43NSA3Ljk1IDE3Ljc1IDE3Ljc1YzAgNC43MS0xLjg3IDkuMjItNS4yIDEyLjU1cy03Ljg0IDUuMi0xMi41NSA1LjJ6IiBmaWxsPSIjNTM1MzUzIi8+PHBhdGggZD0ibTQxIDM2Yy01LjgxIDYuMjMtMTUuMjMgNy40NS0yMi40MyAyLjktNy4yMS00LjU1LTEwLjE2LTEzLjU3LTcuMDMtMjEuNWwtNC45Mi0zLjExYy00Ljk1IDEwLjctMS4xOSAyMy40MiA4Ljc4IDI5LjcxIDkuOTcgNi4zIDIzLjA3IDQuMjIgMzAuNi00Ljg2eiIgZmlsbD0iIzljOWM5YyIvPjxwYXRoIGQ9Im0uMiA1OC40NWMwLS43NS4xMS0xLjQyLjMzLTIuMDFzLjUyLTEuMDkuOTEtMS41Yy4zOC0uNDEuODMtLjczIDEuMzQtLjk0LjUxLS4yMiAxLjA2LS4zMiAxLjY1LS4zMi41NiAwIDEuMDYuMTEgMS41MS4zNS40NC4yMy44MS41IDEuMS44MWwtLjkxIDEuMDFjLS4yNC0uMjQtLjQ5LS40Mi0uNzUtLjU2LS4yNy0uMTMtLjU4LS4yLS45My0uMi0uMzkgMC0uNzMuMDgtMS4wNS4yMy0uMzEuMTYtLjU4LjM3LS44MS42Ni0uMjMuMjgtLjQxLjYzLS41MyAxLjA0LS4xMy40MS0uMTkuODgtLjE5IDEuMzkgMCAxLjA0LjIzIDEuODYuNjggMi40Ni40NS41OSAxLjA2Ljg4IDEuODQuODguNDEgMCAuNzctLjA3IDEuMDctLjIzcy41OS0uMzkuODUtLjY4bC45MSAxYy0uMzguNDMtLjguNzYtMS4yOC45OS0uNDcuMjItMSAuMzQtMS41OC4zNC0uNTkgMC0xLjEzLS4xLTEuNjQtLjMxLS41LS4yLS45NC0uNTEtMS4zMS0uOTEtLjM4LS40LS42Ny0uOS0uODgtMS40OC0uMjItLjU5LS4zMy0xLjI2LS4zMy0yLjAyem04LjQtNS4zM2gxLjYxdjIuNTRsLS4wNSAxLjMzYy4yOS0uMjcuNjEtLjUxLjk2LS43MnMuNzYtLjMxIDEuMjQtLjMxYy43MyAwIDEuMjcuMjMgMS42MS43MS4zMy40Ny41IDEuMTQuNSAyLjAydjQuMzFoLTEuNjF2LTQuMWMwLS41Ny0uMDgtLjk3LS4yNS0xLjIxLS4xNy0uMjMtLjQ1LS4zNS0uODMtLjM1LS4zIDAtLjU2LjA4LS43OS4yMi0uMjMuMTUtLjQ5LjM2LS43OC42NHY0LjhoLTEuNjF6bTcuMzcgNi40NWMwLS41Ni4wOS0xLjA2LjI2LTEuNTEuMTgtLjQ1LjQyLS44My43MS0xLjE0LjI5LS4zLjYzLS41NCAxLjAxLS43MS4zOS0uMTcuNzgtLjI1IDEuMTgtLjI1LjQ3IDAgLjg4LjA4IDEuMjMuMjQuMzYuMTYuNjUuMzguODkuNjdzLjQyLjYzLjU0IDEuMDNjLjEyLjQxLjE4Ljg0LjE4IDEuMzIgMCAuMzItLjAyLjU3LS4wNy43NmgtNC4zNmMuMDcuNjIuMjkgMS4xLjY1IDEuNDQuMzYuMzMuODIuNSAxLjM4LjUuMjkgMCAuNTctLjA0LjgzLS4xM3MuNTEtLjIxLjc2LS4zN2wuNTUgMS4wMWMtLjMzLjIxLS42OS4zOS0xLjA5LjUzLS40MS4xNC0uODMuMjEtMS4yNi4yMS0uNDggMC0uOTItLjA4LTEuMzQtLjI1LS40MS0uMTYtLjc2LS40LTEuMDctLjctLjMxLS4zMS0uNTUtLjY5LS43Mi0xLjEzLS4xOC0uNDQtLjI2LS45NS0uMjYtMS41MnptNC42LS42MmMwLS41NS0uMTEtLjk4LS4zNC0xLjI4LS4yMy0uMzEtLjU4LS40Ny0xLjA2LS40Ny0uNDEgMC0uNzcuMTUtMS4wNy40NS0uMzEuMjktLjUuNzMtLjU4IDEuM3ptMi41LjYyYzAtLjU3LjA5LTEuMDguMjgtMS41My4xOC0uNDQuNDMtLjgyLjc1LTEuMTNzLjY5LS41NCAxLjEtLjcxYy40Mi0uMTYuODUtLjI0IDEuMzEtLjI0LjQ1IDAgLjg0LjA4IDEuMTcuMjNzLjYxLjM0Ljg1LjU3bC0uNzcgMS4wMmMtLjE5LS4xNi0uMzgtLjI4LS41Ni0uMzctLjE5LS4wOS0uMzktLjE0LS42MS0uMTQtLjU2IDAtMS4wMS4yMS0xLjM1LjYzLS4zNS40MS0uNTIuOTctLjUyIDEuNjcgMCAuNjkuMTcgMS4yNC41MSAxLjY2LjM0LjQxLjc4LjYyIDEuMzIuNjIuMjggMCAuNTQtLjA2Ljc4LS4xNy4yNC0uMTIuNDUtLjI2LjY0LS40MmwuNjcgMS4wM2MtLjMzLjI5LS42OS41MS0xLjA4LjY1LS4zOS4xNS0uNzguMjMtMS4xOC4yMy0uNDYgMC0uOS0uMDgtMS4zMS0uMjQtLjQtLjE2LS43NS0uMzktMS4wNS0uN3MtLjUzLS42OS0uNy0xLjEzYy0uMTctLjQ1LS4yNS0uOTYtLjI1LTEuNTN6bTYuOTEtNi40NWgxLjU4djYuMTdoLjA1bDIuNTQtMy4xNmgxLjc3bC0yLjM1IDIuOCAyLjU5IDQuMDdoLTEuNzVsLTEuNzctMi45OC0xLjA4IDEuMjN2MS43NWgtMS41OHptMTMuNjkgMS4yN2MtLjI1LS4xMS0uNS0uMTctLjc1LS4xNy0uNTggMC0uODcuMzktLjg3IDEuMTZ2Ljc1aDEuMzR2MS4yN2gtMS4zNHY1LjZoLTEuNjF2LTUuNmgtLjkydi0xLjJsLjkyLS4wN3YtLjcyYzAtLjM1LjA0LS42OC4xMy0uOTguMDgtLjMxLjIxLS41Ny40LS43OXMuNDItLjM5LjcxLS41MWMuMjgtLjEyLjYzLS4xOCAxLjA0LS4xOC4yNCAwIC40OC4wMi42OS4wNy4yMi4wNS40MS4xLjU3LjE3em0uNDggNS4xOGMwLS41Ny4wOS0xLjA4LjI3LTEuNTMuMTctLjQ0LjQxLS44Mi43Mi0xLjEzLjMtLjMxLjY1LS41NCAxLjA0LS43MS4zOS0uMTYuOC0uMjQgMS4yMy0uMjRzLjg0LjA4IDEuMjQuMjRjLjQuMTcuNzQuNCAxLjA0Ljcxcy41NC42OS43MiAxLjEzYy4xOS40NS4yOC45Ni4yOCAxLjUzcy0uMDkgMS4wOC0uMjggMS41M2MtLjE4LjQ0LS40Mi44Mi0uNzIgMS4xM3MtLjY0LjU0LTEuMDQuNy0uODEuMjQtMS4yNC4yNC0uODQtLjA4LTEuMjMtLjI0LS43NC0uMzktMS4wNC0uN2MtLjMxLS4zMS0uNTUtLjY5LS43Mi0xLjEzLS4xOC0uNDUtLjI3LS45Ni0uMjctMS41M3ptMS42NSAwYzAgLjY5LjE0IDEuMjQuNDMgMS42Ni4yOC40MS42OC42MiAxLjE4LjYyLjUxIDAgLjktLjIxIDEuMTktLjYyLjI5LS40Mi40NC0uOTcuNDQtMS42NiAwLS43LS4xNS0xLjI2LS40NC0xLjY3LS4yOS0uNDItLjY4LS42My0xLjE5LS42My0uNSAwLS45LjIxLTEuMTguNjMtLjI5LjQxLS40My45Ny0uNDMgMS42N3ptNi40OC0zLjQ0aDEuMzNsLjEyIDEuMjFoLjA1Yy4yNC0uNDQuNTQtLjc5Ljg4LTEuMDIuMzUtLjI0LjctLjM2IDEuMDctLjM2LjMyIDAgLjU5LjA1Ljc4LjE0bC0uMjggMS40LS4zMy0uMDljLS4xMS0uMDEtLjIzLS4wMi0uMzgtLjAyLS4yNyAwLS41Ni4xLS44Ni4zMXMtLjU1LjU4LS43NyAxLjF2NC4yaC0xLjYxem0tNDcuODcgMTVoMS42MXY0LjFjMCAuNTcuMDguOTcuMjUgMS4yLjE3LjI0LjQ0LjM1LjgxLjM1LjMgMCAuNTctLjA3LjgtLjIyLjIyLS4xNS40Ny0uMzkuNzMtLjczdi00LjdoMS42MXY2Ljg3aC0xLjMybC0uMTItMS4wMWgtLjA0Yy0uMy4zNi0uNjMuNjQtLjk4Ljg2LS4zNS4yMS0uNzYuMzItMS4yNC4zMi0uNzMgMC0xLjI3LS4yNC0xLjYxLS43MS0uMzMtLjQ3LS41LTEuMTQtLjUtMi4wMnptOS40NiA3LjQzdjIuMTZoLTEuNjF2LTkuNTloMS4zM2wuMTIuNzJoLjA1Yy4yOS0uMjQuNjEtLjQ1Ljk3LS42My4zNS0uMTcuNzItLjI2IDEuMS0uMjYuNDMgMCAuODEuMDggMS4xNS4yNC4zMy4xNy42MS40Ljg0LjcxLjI0LjMxLjQxLjY4LjUzIDEuMTEuMTMuNDIuMTkuOTEuMTkgMS40NCAwIC41OS0uMDkgMS4xMS0uMjUgMS41Ny0uMTYuNDctLjM4Ljg1LS42NSAxLjE2LS4yNy4zMi0uNTguNTYtLjk0LjczLS4zNS4xNi0uNzIuMjUtMS4xLjI1LS4zIDAtLjYtLjA3LS45LS4ycy0uNTktLjMxLS44Ny0uNTZ6bTAtMi4zYy4yNi4yMi41LjM3LjczLjQ1LjI0LjA5LjQ2LjEzLjY2LjEzLjQ2IDAgLjg0LS4yIDEuMTUtLjYuMzEtLjM5LjQ2LS45OC40Ni0xLjc3IDAtLjY5LS4xMi0xLjIyLS4zNS0xLjYxLS4yMy0uMzgtLjYxLS41Ny0xLjEzLS41Ny0uNDkgMC0uOTkuMjYtMS41Mi43N3ptNS44Ny0xLjY5YzAtLjU2LjA4LTEuMDYuMjUtMS41MS4xNi0uNDUuMzctLjgzLjY1LTEuMTQuMjctLjMuNTgtLjU0LjkzLS43MXMuNzEtLjI1IDEuMDgtLjI1Yy4zOSAwIC43My4wNyAxIC4yLjI3LjE0LjU0LjMyLjgxLjU1bC0uMDYtMS4xdi0yLjQ5aDEuNjF2OS44OGgtMS4zM2wtLjExLS43NGgtLjA2Yy0uMjUuMjUtLjU0LjQ2LS44OC42NC0uMzMuMTgtLjY5LjI3LTEuMDYuMjctLjg3IDAtMS41Ni0uMzItMi4wNy0uOTVzLS43Ni0xLjUxLS43Ni0yLjY1em0xLjY3LS4wMWMwIC43NC4xMyAxLjMxLjQgMS43LjI2LjM4LjY1LjU4IDEuMTUuNTguNTEgMCAuOTktLjI2IDEuNDQtLjc3di0zLjIxYy0uMjQtLjIxLS40OC0uMzYtLjctLjQ1LS4yMy0uMDgtLjQ2LS4xMi0uNy0uMTItLjQ1IDAtLjgyLjE5LTEuMTMuNTktLjMxLjM5LS40Ni45NS0uNDYgMS42OHptNi4zNSAxLjU5YzAtLjczLjMyLTEuMy45Ny0xLjcxLjY0LS40IDEuNjctLjY4IDMuMDgtLjg0IDAtLjE3LS4wMi0uMzQtLjA3LS41MS0uMDUtLjE2LS4xMi0uMy0uMjItLjQzcy0uMjItLjIyLS4zOC0uM2MtLjE1LS4wNi0uMzQtLjEtLjU4LS4xLS4zNCAwLS42OC4wNy0xIC4ycy0uNjMuMjktLjkzLjQ3bC0uNTktMS4wOGMuMzktLjI0LjgxLS40NSAxLjI4LS42My40Ny0uMTcuOTktLjI2IDEuNTQtLjI2Ljg2IDAgMS41MS4yNSAxLjkzLjc2cy42MyAxLjI1LjYzIDIuMjF2NC4wN2gtMS4zMmwtLjEyLS43NmgtLjA1Yy0uMy4yNy0uNjMuNDgtLjk4LjY2cy0uNzMuMjctMS4xNC4yN2MtLjYxIDAtMS4xLS4xOS0xLjQ4LS41Ni0uMzgtLjM2LS41Ny0uODUtLjU3LTEuNDZ6bTEuNTctLjEyYzAgLjMuMDkuNTMuMjcuNjcuMTkuMTQuNDIuMjEuNzEuMjEuMjggMCAuNTQtLjA3Ljc3LS4ycy40OC0uMzEuNzMtLjU2di0xLjU0Yy0uNDcuMDYtLjg2LjEzLTEuMTguMjMtLjMxLjA5LS41Ny4xOS0uNzYuMzFzLS4zMy4yNS0uNDEuNGMtLjA5LjE1LS4xMy4zMS0uMTMuNDh6bTYuMjktMy42M2gtLjk4di0xLjJsMS4wNi0uMDcuMi0xLjg4aDEuMzR2MS44OGgxLjc1djEuMjdoLTEuNzV2My4yOGMwIC44LjMyIDEuMi45NyAxLjIuMTIgMCAuMjQtLjAxLjM3LS4wNC4xMi0uMDMuMjQtLjA3LjM0LS4xMWwuMjggMS4xOWMtLjE5LjA2LS40LjEyLS42NC4xNy0uMjMuMDUtLjQ5LjA4LS43Ni4wOC0uNCAwLS43NC0uMDYtMS4wMi0uMTgtLjI3LS4xMy0uNDktLjMtLjY3LS41Mi0uMTctLjIxLS4zLS40OC0uMzctLjc4LS4wOC0uMy0uMTItLjY0LS4xMi0xLjAxem00LjM2IDIuMTdjMC0uNTYuMDktMS4wNi4yNy0xLjUxcy40MS0uODMuNzEtMS4xNGMuMjktLjMuNjMtLjU0IDEuMDEtLjcxLjM5LS4xNy43OC0uMjUgMS4xOC0uMjUuNDcgMCAuODguMDggMS4yMy4yNC4zNi4xNi42NS4zOC44OS42N3MuNDIuNjMuNTQgMS4wM2MuMTIuNDEuMTguODQuMTggMS4zMiAwIC4zMi0uMDIuNTctLjA3Ljc2aC00LjM3Yy4wOC42Mi4yOSAxLjEuNjUgMS40NC4zNi4zMy44Mi41IDEuMzguNS4zIDAgLjU4LS4wNC44NC0uMTMuMjUtLjA5LjUxLS4yMS43Ni0uMzdsLjU0IDEuMDFjLS4zMi4yMS0uNjkuMzktMS4wOS41M3MtLjgyLjIxLTEuMjYuMjFjLS40NyAwLS45Mi0uMDgtMS4zMy0uMjUtLjQxLS4xNi0uNzctLjQtMS4wOC0uNy0uMy0uMzEtLjU0LS42OS0uNzItMS4xMy0uMTctLjQ0LS4yNi0uOTUtLjI2LTEuNTJ6bTQuNjEtLjYyYzAtLjU1LS4xMS0uOTgtLjM0LTEuMjgtLjIzLS4zMS0uNTgtLjQ3LTEuMDYtLjQ3LS40MSAwLS43Ny4xNS0xLjA4LjQ1LS4zMS4yOS0uNS43My0uNTcgMS4zem0zLjAxIDIuMjNjLjMxLjI0LjYxLjQzLjkyLjU3LjMuMTMuNjMuMi45OC4yLjM4IDAgLjY1LS4wOC44My0uMjNzLjI3LS4zNS4yNy0uNmMwLS4xNC0uMDUtLjI2LS4xMy0uMzctLjA4LS4xLS4yLS4yLS4zNC0uMjgtLjE0LS4wOS0uMjktLjE2LS40Ny0uMjNsLS41My0uMjJjLS4yMy0uMDktLjQ2LS4xOC0uNjktLjMtLjIzLS4xMS0uNDQtLjI0LS42Mi0uNHMtLjMzLS4zNS0uNDUtLjU1Yy0uMTItLjIxLS4xOC0uNDYtLjE4LS43NSAwLS42MS4yMy0xLjEuNjgtMS40OS40NC0uMzggMS4wNi0uNTcgMS44My0uNTcuNDggMCAuOTEuMDggMS4yOS4yNXMuNzEuMzYuOTkuNTdsLS43NC45OGMtLjI0LS4xNy0uNDktLjMyLS43My0uNDItLjI1LS4xMS0uNTEtLjE2LS43OC0uMTYtLjM1IDAtLjYuMDctLjc2LjIxLS4xNy4xNS0uMjUuMzMtLjI1LjU0IDAgLjE0LjA0LjI2LjEyLjM2cy4xOC4xOC4zMS4yNmMuMTQuMDcuMjkuMTQuNDYuMjFsLjU0LjE5Yy4yMy4wOS40Ny4xOC43LjI5cy40NC4yNC42NC40Yy4xOS4xNi4zNC4zNS40Ni41OC4xMS4yMy4xNy41LjE3LjgyIDAgLjMtLjA2LjU4LS4xNy44My0uMTIuMjYtLjI5LjQ4LS41MS42OC0uMjMuMTktLjUxLjM0LS44NC40NS0uMzQuMTEtLjcyLjE3LTEuMTUuMTctLjQ4IDAtLjk1LS4wOS0xLjQxLS4yNy0uNDYtLjE5LS44Ni0uNDEtMS4yLS42OHoiIGZpbGw9IiM1MzUzNTMiLz48L2c+PC9zdmc+)

### Cite this article

Takamatsu, N., Muramatsu, H., Abe, S. *et al.* New GEONET analysis strategy at GSI: daily coordinates of over 1300 GNSS CORS in Japan throughout the last quarter century.
*Earth Planets Space* **75**, 49 (2023). https://doi.org/10.1186/s40623-023-01787-7

[Download citation](https://citation-needed.springer.com/v2/references/10.1186/s40623-023-01787-7?format=refman&flavour=citation)

Received: 19 March 2022

Accepted: 17 February 2023

Published: 06 April 2023

Version of record: 06 April 2023

DOI: https://doi.org/10.1186/s40623-023-01787-7

### Share this article

Anyone you share the following link with will be able to read this content:

Sorry, a shareable link is not currently available for this article.

Provided by the Springer Nature SharedIt content-sharing initiative

### Keywords

### Profiles

## Associated Content

Part of a collection:

### [Recent Advances in Scientific Application of GNSS Array Data](https://link.springer.com/collections/ajagaahijc)

### [Frontier Letters](https://link.springer.com/collections/hcgdfdgjih)

### [Section on Geodesy](https://link.springer.com/collections/ieaehaffdd)

Advertisement

## Search

## Navigation

## Footer Navigation

### Discover content

### Publish with us

### Products and services

### Our brands

### Corporate Navigation

109.79.66.197

Not affiliated

![Springer Nature](/oscar-static/images/logo-springernature-white-0689727e50.svg)

© 2026 Springer Nature