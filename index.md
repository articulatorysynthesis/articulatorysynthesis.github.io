# Deep Speech Synthesis from Articulatory Features

**Link to the codebase will be added soon!**

### EMA-to-Speech

| **Text** | **HiFi-CAR** | **Spec-Int** | **Ground Truth** |
| --- | --- | --- | --- |
| But this yard. | <audio controls=""> <source src="samples/hifi-car/mngu0_s1_0060_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mel/mngu0_s1_0060_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mngu0_s1_0060.mp3"> </audio> | 
| My whole house shook. | <audio controls=""> <source src="samples/hifi-car/mngu0_s1_0080_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mel/mngu0_s1_0080_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mngu0_s1_0080.mp3"> </audio> | 
| The prime minister dismissed any suggestion that the war was in any way to do with oil. | <audio controls=""> <source src="samples/hifi-car/mngu0_s1_0320_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mel/mngu0_s1_0320_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mngu0_s1_0320.mp3"> </audio> | 
| Dirt will fly. | <audio controls=""> <source src="samples/hifi-car/mngu0_s1_0420_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mel/mngu0_s1_0420_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mngu0_s1_0420.mp3"> </audio> | 
| The horrible sound remains in my ears. | <audio controls=""> <source src="samples/hifi-car/mngu0_s1_0800_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mel/mngu0_s1_0800_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mngu0_s1_0800.mp3"> </audio> | 
| The observer saw no evidence of fighting. | <audio controls=""> <source src="samples/hifi-car/mngu0_s1_0880_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mel/mngu0_s1_0880_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mngu0_s1_0880.mp3"> </audio> | 
| No negotiations. | <audio controls=""> <source src="samples/hifi-car/mngu0_s1_1020_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mel/mngu0_s1_1020_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mngu0_s1_1020.mp3"> </audio> | 
| These guys just played awesome today. | <audio controls=""> <source src="samples/hifi-car/mngu0_s1_1040_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mel/mngu0_s1_1040_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mngu0_s1_1040.mp3"> </audio> | 
| People involved in commercial fish work may have brought them here. | <audio controls=""> <source src="samples/hifi-car/mngu0_s1_1120_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mel/mngu0_s1_1120_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mngu0_s1_1120.mp3"> </audio> | 
| But with oil exploration having reached a plateau there would be an inevitable rise in world prices. | <audio controls=""> <source src="samples/hifi-car/mngu0_s1_1240_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mel/mngu0_s1_1240_gen.mp3"> </audio> | <audio controls=""> <source src="samples/mngu0_s1_1240.mp3"> </audio> | 

### Interpolation Experiments

| **Text** | **HiFi-CAR** | **Ground Truth** |
| --- | --- | --- |
| "ra" to "na" | <audio controls=""> <source src="samples/interp/hifi/r_a_n_a.mp3"> </audio> | <audio controls=""> <source src="samples/interp/true/r_a_n_a.mp3"> </audio> | 
| "na" to "la" | <audio controls=""> <source src="samples/interp/hifi/n_a_l_a.mp3"> </audio> | <audio controls=""> <source src="samples/interp/true/n_a_l_a.mp3"> </audio> | 
| "la" to "ra" | <audio controls=""> <source src="samples/interp/hifi/l_a_r_a.mp3"> </audio> | <audio controls=""> <source src="samples/interp/true/l_a_r_a.mp3"> </audio> | 
| "ra" to "ja" | <audio controls=""> <source src="samples/interp/hifi/r_a_j_a.mp3"> </audio> | <audio controls=""> <source src="samples/interp/true/r_a_j_a.mp3"> </audio> | 
| "ta" to "tu" | <audio controls=""> <source src="samples/interp/hifi/ta_tu.mp3"> </audio> | <audio controls=""> <source src="samples/interp/true/ta_tu.mp3"> </audio> | 
| "tu" to "ti" | <audio controls=""> <source src="samples/interp/hifi/tu_ti.mp3"> </audio> | <audio controls=""> <source src="samples/interp/true/tu_ti.mp3"> </audio> | 
| "ti" to "ta" | <audio controls=""> <source src="samples/interp/hifi/ti_ta.mp3"> </audio> | <audio controls=""> <source src="samples/interp/true/ti_ta.mp3"> </audio> | 
