# looking-represents-choosing

Hagihara, H., Ienaga, N., Terayama, K., Moriguchi, Y., & & Sakagami, M. (in press). Looking represents choosing in toddlers: Exploring the equivalence between multimodal measures in forced-choice tasks. *Infancy*. https://doi.org/10.1111/infa.12377


## Dataset files
- **looking_represents_choosing_phase1.csv**
	- Dataset for Phase 1 (model construction)
	- Videos of 369 trials with 24 monolingual Japanese toddlers aged 18–23 months
	- 15 trials (8 toddlers) were excluded for lack of explicit pointing responses
- **looking_represents_choosing_phase2.csv**
	- Dataset for Phase 2 (model validation)
	- Videos of 183 trials with 12 monolingual Japanese toddlers aged 18–23 months
	- 9 trials (5 toddlers) were excluded for lack of explicit pointing responses
- **looking_represents_choosing_phase3.csv**
	- Dataset for Phase 3 (model application to data with no-pointing responses)
	- Videos of 176 trials with 12 monolingual Japanese toddlers aged 18–22 months
	- 16 trials (5 toddlers) were excluded because they showed explicit pointing behavior


## Description of labels
| label | description |
|:----|:----|
| id | Participants' IDs |
| sex | Participants' gender |
| ageM | Participants' age in months |
| trialOrd | The order of the trials among the same participants (1-16) |
| frm | The order of the frames in the same trial between the end of the question and 2 sec thereafter (30 fps) |
| idtrialOrd | Concatenated variable of participants' ID and the order of the trials (i.e., "id" _ "trialOrd") |
| trialNum | The ID of stimulus presented in the trial |
| pointLR | Participants' pointing responses (left or right). For Phase 3, this variable was estimated by human raters |
| conf | Confidence value calculated by OpenFace. IP indicates linear interpolation due to the failure of face detection |
| faceAngRaw | Raw horizontal angle of participants' face (radian, positive values indicate looking right side) |
| faceAngMod | Compensated horizontal angle of participants' face |
| gazeAngRaw | Raw horizontal angle of participants' gaze (radian, positive values indicate looking right side) |
| gazeAngMod | Compensated horizontal angle of participants' gaze |
| pointFrm | The frame when participants showed pointing responses (Phases 1 and 2 only) |
| pointLRConf | Confidence value about the estimation of pointing responses by human raters (Phase 3 only; using 5-point Likert scale, 5 indicates high confidence) |


## Contact
If you have any questions, please email at hiromichi.h <at> gmail.com (please replace <at> with @).							
