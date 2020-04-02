# COVID-19 Imaging AI

An organized collection of data, initiatives, software and papers for 
COVID-19 imaging AI.

## :bar_chart: Data

Name | Modality | Format | #scans | Labels | Clinical info | Accessibility
-----|----------|--------|-----------------|--------|---------------|--------------
[SIRM](https://www.sirm.org/category/senza-categoria/covid-19/) | XR, CT | jpeg | 60 | :x: | age, medication, history, radiology report | :heavy_check_mark: [NifTI](http://medicalsegmentation.com/covid19/) 
[RSNA](https://cases.rsna.org/coronavirus) | CT	| png | 11 | :x: | extensive: age, gender, history, presentation, physical exam, diagnostic testing, diagnosis | :wavy_dash: downloadable, but not in batch
[covid-chestxray-dataset](https://github.com/ieee8023/covid-chestxray-dataset) | CT, XR | jpeg, dcm, png | 200+ | :heavy_check_mark: | extensive: age, gender, scan date, report when available | :heavy_check_mark: downloadable
[coronacases.org](https://coronacases.org) | CT | dcm | 10 | :x: | | :x: not downloadable, only viewer
[Radiopaedia](https://radiopaedia.org/search?lang=us&q=covid&scope=cases) | CT, XR | jpeg | 34 | :x: | age, symptoms, PCR | :wavy_dash: download as jpeg per slice

### :card_file_box: Dataset aggregators/lists

Name | Description
-----|------------
[covid19-images](https://github.com/coyotespike/covid19-images) | Repository with other datasets as submodules. Soon will include dataloaders for TensorFlow, PyTorch, etc.
[covid-dataset](https://github.com/arthurfigueiredo/covid-dataset) | Repository with links to other datasets, also non-COVID CT and XR.

## :world_map: (Inter)national initiatives

Name | Goal | Partners | Companies | Freely deployed\*
-----|------|----------|-----------|------------------
[Imaging COVID-19 AI](https://imagingcovid19ai.eu/) | Develop AI solution for CT | 20 european hospitals (unclear which), EuSoMII, NCI | Quibim, Robovision | :wavy_dash:
[RSNA Data Repository](https://press.rsna.org/timssnet/media/pressreleases/14_pr_target.cfm?ID=2167) | Build open data repository for research and education | EuSoMII | | :wavy_dash:
[Covid19Challenge](https://www.covid19challenge.eu) | Collect data and develop AI solution for CT | LMU, TUM, BBF | M3i, ImFusion, Smart Reporting | :wavy_dash:, best models open-source after challenge 
[Open COVID-19 Chest-AI repository](https://doradiology.com/covid-ai/index-notyetlive.html) | Free and open data repository | NVvR, UMC Utrecht | Segmed | :wavy_dash:
[RDA COVID-19 Working Group](https://www.rd-alliance.org/groups/rda-covid19) | Define guidelines on data sharing and re-use | | |

### \* 
Symbol | Meaning
-------|--------
:wavy_dash: | Intention to deploy freely is advertised
:heavy_check_mark: | Solution is confirmed to be available

## :minidisc: Software

### :mag: Classification/detection
Owner/developer | url | Partners | Modality | Format | Public | Integration | Validation/paper
----------------|-----|----------|----------|--------|--------|-------------|-----------------
[COVnet](https://github.com/bkong999/COVNet) | [:octocat:](https://github.com/bkong999/COVNet) | | CT | dcm | :heavy_check_mark: | | [:computer_mouse:](https://pubs.rsna.org/doi/10.1148/radiol.2020200905)
[DarwinAI](https://www.darwinai.com/) | [:octocat:](https://github.com/lindawangg/COVID-Net/) | | XR | |:heavy_check_mark: | | [:computer_mouse:](https://arxiv.org/abs/2003.09871)
[CTAngel](http://121.40.75.149/znyx-ncov/index#/app/index) | [:computer_mouse:](http://121.40.75.149/znyx-ncov/index#/app/index) | Renmin Hospital of Wuhan University, Wuhan EndoAngel | CT | jpeg (submit per slice) | :heavy_check_mark: | Browser | [:computer_mouse:](https://www.medrxiv.org/content/medrxiv/early/2020/02/26/2020.02.25.20021568.full.pdf)
[Quibim](https://quibim.com) | [:computer_mouse:](https://imagingcovid19.quibim.com) | [Imaging COVID-19 AI](https://imagingcovid19ai.eu/) | CT, XR | dcm | :heavy_check_mark: | Browser |
[Alibaba Cloud](https://alibabacloud.com) | [:computer_mouse:](https://www.alibabacloud.com/solutions/ct-image-analytics) | | CT | dcm | :wavy_dash: apply via mail | Cloud |
[Behold.ai](https://behold.ai) | [:computer_mouse:](https://behold.ai/covid-19/) | | XR | jpeg | :question: | :question: | 

### :mortar_board: Educational
Owner/developer | url | Partners | Modality | Format | Public | Integration | Validation/paper
----------------|-----|----------|----------|--------|--------|-------------|-----------------
[CIMAR](https://cimar.co.uk/) | [:computer_mouse:](https://bsticovid19.cimar.co.uk/) | | CT, XR | |:heavy_check_mark: | Browser | 
[DetectEDx](https://www.detectedx.com/) | [:computer_mouse:](https://www.detectedx.com/) | University of Sydney | CT | dcm | :heavy_check_mark: | Browser | 

## :page_facing_up: Papers

### CT

Theme | Link | Title | Journal
--------|-------|-------|-----
AI | [:computer_mouse:](https://arxiv.org/abs/2003.0503) | Rapid AI Development Cycle for the Coronavirus (COVID-19) Pandemic: Initial Results for Automated Detection & Patient Monitoring using Deep Learning CT Image Analysis | arXiv

### X-Ray

## Contribute

Know of anything that should be listed here? Feel free to submit a pull
request or open an issue for anything else!

You can also get in touch via [email](mailto:bram.dewilde@radboudumc.nl).
