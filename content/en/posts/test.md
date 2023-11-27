+++
title = 'Preparations for the first "RISC-V Software Porting and Optimization Championship" have been officially launched, sponsors are sincerely invited'
date = 2023-11-27T01:16:43+08:00
toc=true
featured_image = 'images/test.jpg'
omit_header_text = true
slug = '000'
+++

TEST FILE

## Event name

Chinese name: RISC-V Software Porting and Optimization Championship

English name: RISC-V Software Porting and Optimization Championship

Russian name: RISC-V

Japanese name: RISC-V ソフトウェアの transplantation and optimization チャンピオンシップ

Korean name: RISC-V 소프트웨어포팅및최적화챔피언십

## Background and goals

RISC-V has already shipped billions in MCU/IoT and other fields, and is challenging large computing power fields such as desktop computing, HPC, AI, and data centers. Compared with the software ecosystem in the embedded and IoT fields, the desktop and server software ecosystem is rich, and the workload that needs to be transplanted and optimized is huge.

In the past few years, PLCT Laboratory, together with global technical teams and contributors, has invested a lot of money and manpower to improve the RISC-V open source software ecosystem and achieved high stage results. Today, almost all popular Linux operating system distributions have or are actively supporting the RISC-V architecture. Toolchains and runtimes such as GNU Toolchain, Clang/LLVM, OpenJDK, V8, Spidermonkey, etc. are all able to run stably on the RISC-V platform. .

At present, the open source software community's running speed on RISC-V hardware has not reached the optimization level of X86 or Arm64, and more enthusiastic developers need to participate. In order to promote the faster development of the RISC-V software ecosystem and attract more developers to join the RISC-V ecosystem, PLCT Laboratory launched the "RISC-V Software Porting and Optimization Championship" event. This championship will focus on the desktop and server software ecology, and publicly propose a series of competition questions in multiple aspects such as compilers, runtime environments, and AI software stacks, and invite developers from around the world to complete challenges and win prizes.

## Event organization structure

Sponsor: PLCT Laboratory (affiliated to the Intelligent Software Research Center of the Institute of Software, Chinese Academy of Sciences)

Organizer: Hangzhou Quancheng Intelligent Software Co., Ltd.

Co-organizer: RISC-V Chinese Community (CNRV)

Note: As the event planning progresses, the event organizational structure may change. Please refer to the latest push from CNRV’s subsequent official account for reference.

## Tournament format

The competition is divided into two forms: **Adaptation Capture the Flag Competition** and **Optimization Race**.

**Adapt Capture the Flag Competition** generally sets a software porting goal. The software (or component) **has not yet been ported** to the RISC-V architecture, and the first one to complete the open source porting work and submit it to the designated warehouse The team (or individual) with the highest address wins. The organizer sets up a dedicated warehouse for each competition topic and accepts submissions from contestants. The first contestant or team to completely pass the test and submit it to the organizer's warehouse is the winner. The ownership and authorship rights of the submitted competition code belong to the contestant himself (or the corresponding open source project community for transplantation). The organizer encourages contestants to contribute code back to the upstream community (upstream).

**Optimization Competition** refers to setting an **Optimization Evaluation Index** for each competition question, optimizing against the specified benchmark, and setting a submission deadline. Among all results submitted before the competition deadline, the team with the best indicators wins.

According to the number of participants, this championship is divided into two forms: "individual group" and "team group". In the individual group, the main work during the competition is required to be completed by the contestant himself, and he will be entitled to the prize alone; if there are more than two people participating, it will be a team form. There is no limit on the number of people in the team group, and the bonus distribution ratio is determined by the participating teams.

## Championship schedule (tentative)
Before October 31, 2023: Sponsor solicitation stage

November 1 – November 30, 2023: Competition launch, public release of competition questions

December 1, 2023 – February 16, 2024: Competition registration and competition stage

February 17, 2024 – March 1, 2024: The organizer will reproduce the results of the competition and announce the winner’s list

Early April 2024 (specific date to be determined): The 1st RISC-V Software Porting and Optimization Championship Award Ceremony and RISC-V Technology Seminar

## **Sponsors are invited**

This competition accepts donations from sponsors. The organizer welcomes inquiries and negotiations from global RISC-V manufacturers.

### Sponsor participation forms and rights
Sponsors can participate in the setting of competition questions and bonuses, and they can be exposed during the competition and in the announcement of award competitions.

The minimum sponsorship amount for sponsors is RMB 200,000, and the maximum sponsorship amount is (temporarily) limited to RMB 1 million. Sponsors can negotiate and customize according to the number of game questions and the amount of prizes.

Sponsor's sponsorship funds consist of:

- 30% of the sponsorship fee will be used for competition preparation costs and personnel, organization and publicity costs.

- 70% of the sponsorship fee will be used as bonuses distributed to participants/teams.

Sponsor benefits include the following:

- **Specify specific hardware devices or platforms as the target platform for porting and optimization of the competition;**

- Participate in the organizer's competition topic design and share the rights derived from the competition topic (to be refined);

- Specify the bonus distribution ratio and participate in the organizing committee's competition result reappearance confirmation process;

- Participate in the championship award ceremony and RISC-V technology seminar, including 20 minutes of rights promotion, recruitment promotion, booth display, dinner invitation, etc.;

- Participate in other competition-related publicity activities organized by the organizer, including offline promotions, online live broadcasts, etc.;

If your company is interested in sponsoring, please contact the organizer by email at the following address:

- **Email address: "Wei Wu"** wuwei2016@iscas.ac.cn
- **"Wei Wu" email title: "[RVPOC] Sponsor + your_company_name"**

### Contest topic (sample)

The competition questions are currently being collected and selected. All participants in the RISC-V ecological community are welcome to contribute contest topics. The topic of the competition can be "Software I hope to be able to use" or "I hope such and such software/service can be faster (to what extent)". You are welcome to contact the organizer via email at the following address for submission:

- **"Wei Wu"** wuwei2016@iscas.ac.cn
- **"Wei Wu" email title: "[RVPOC] WISHLIST + software name"**

#### Transplantation category (the award winner/award winning team is required to open source and contribute to upstream)

| Technical classification | Title | Reference amount (before tax/RMB) | Verification platform | Sponsor |
| -------- | ----------------------------------- | -------------------- | ----------- | -------- |
| Runtime | Mono on RISC-V | 50,000 | SG2042 QEMU | TBA |
| Runtime | WASM for RISC-V V-extension on V8 | 100,000 | SG2042 QEMU | TBA |
| Runtime | Welcome to provide suggestions for competition questions! | | | |

#### Optimization category (divided into open source and closed source tracks, only the open source track provides bonuses)

| Technical classification | Title | Reference amount (before tax/RMB) | Verification platform | Sponsor |
| ------ | ---------- | -------------------- | -------- | -------- |
| JS Engine | Firefox Kraken benchmark optimization | 5,000 | LicheePi 4A SG2042 | TBD |
| JS Engine | Use RISC-V B-ext to optimize the bit operation operations of the V8 engine | 30,000 | Unmatched SG2042 TH1520 | TBD |
| Games | OpenRA games running on SG2042 platform in fps | 100,000 | SG2042 SG2044 | TBD |
| rvv0p7 | Provide a set of translation tools or systems so that programs using RVV<sub>1.0</sub> extended instructions can run on the RVV~0.7~ hardware architecture with the best possible performance | 200,000 | | TBD |
| rvv0p7 | Welcome to provide suggestions for competition questions! | | | |

### Organization of the Competition Result Determination Committee

Around each competition topic, the organizer (PLCT Laboratory) will organize a public identification technical committee, inviting well-known developers in the industry, sponsor representatives, and test volunteers to evaluate and reproduce the results.

### Championship Award Ceremony and RISC-V Technology Seminar

Time: Early April 2024
Location: Hangzhou (to be determined, venue sponsorship is welcome)
Format: Offline, seminar format, full day.
Agenda: to be announced in March 2024.

Participation instructions (continuously updated)

1. This competition accepts both individual and group participation. There is no limit on the number of group registrations.

2. In this competition, the optimization questions are divided into two tracks: open source and closed source (commercial). Only the open source track provides bonuses, and the closed source (commercial) track only provides competition ranking records.

3. This event accepts global registration. Winners from Mainland China need to have a bank card in China to receive the prize; participants from non-Mainland China need to provide passport or pass identity information and bank information, and bank payment needs to be supported by SWIFT or CIPS.

4. Please pay attention to follow-up notifications for more registration instructions.
