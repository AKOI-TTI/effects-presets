# Mixxx Custom Effects Presets

## Ethereal Ascend Preset

**Use case:**  This could be used to create a dynamic ethereal and floating effect. Best used for vocals. Twist level knob back and forth to create the effect. 

Effect Chain Configuration

**Name:** **`Ethereal Ascend`**, 

**Mix Mode**: DRY+WET

**Super Parameter Value**: 1 (Fully wet, emphasizing the effects)


**Effects**
1. **Pitch Shift**
- **Enabled Parameter Value: 1**
- **Parameters:**
   - **Pitch:** Linked (Slightly lowering the pitch to create a more ethereal tone) 
   - **Range:** Linked (Extended range for pitch shifting, allowing for more dramatic changes) 
   - **Semitones Mode:** 1 (Enabled to shift in semitones) 
   - **Formant Preserving:** 0 (Disabled to allow for more dramatic pitch changes) 
   - **LinkType:** Pitch and Range(inverted) are linked, meaning adjusting one will affect the other. This could be used to create a dynamic, smooth transition effect when twisting a knob. 

2. **Reverb**
- **Enabled Parameter Value: 1**
- **Parameters:** 
   - **Decay:** 0.8 (Long decay time for a haunting echo) 
   - **Bandwidth:** 0.5 (Narrow bandwidth to reduce high-frequency ringing) 
   - **Damping:** 0.7 (High damping to soften the reverb) 
   - **Send Amount:** 0.6 (Moderate send amount to add ambiance) 
   - **LinkType:** None, each parameter is independent. 

3. **Filter**
- **Enabled Parameter Value: 1** 
- **Parameters:** 
- **LPF (Low Pass Filter):** Linked (Moderate cutoff to add a mellow, ethereal tone) 
   - **Q (Resonance):** 0.5 (Reduced resonance for a smoother filter response) 
   - **HPF (High Pass Filter):** Linked (Low cutoff to remove some low frequencies for clarity) 
   - **LinkType:** LPF is linked to the left channel, and HPF is linked to the right channel, allowing for dynamic control over the cutoff frequencies.

 ## Smooth Transition Preset

**Use case:**  This could be used to create a dynamic, smooth transition effect when twisting level knob. 

Effect Chain Configuration

**Name:** **`Smooth Transition`**, 

**Mix Mode**: DRY/WET

**Super Parameter Value**: 1 (Fully wet, emphasizing the effects)

**Effects**
1. **Bitcrusher**
- **Enabled Parameter Value: 1** 
- **Parameters:** 
   - **Bit Depth:** Linked
   - **Downsample:** Linked (Extremely low downsample rate, further distorting the sound and creating a smooth, grainy texture) 
   - **LinkType:** Both parameters are linked and inverted.
2. **Moog Ladder 4 Filter**
- **Enabled Parameter Value: 1**
- **Parameters:** 
   - **LPF (Low Pass Filter):** Linked (Extremely low cutoff, severely cutting off high frequencies and leaving only the lowest bass tones) 
   - **Resonance:** 1.54534 
   - **HPF (High Pass Filter):** 0.0304851 (Low cutoff, removing some very low frequencies but allowing the bass to pass through) 
   - **LinkType:** The LPF is linked and inverted, meaning adjusting it will inversely affect the cutoff frequency, potentially creating a smooth transition from heavy distortion to more open tones. 
3. **Reverb**
- **Enabled Parameter Value: 1**
- **Parameters:** 
   - **Decay:** Linked 
   - **Bandwidth:** 1 (Full bandwidth, retaining all frequencies in the reverb) 
   - **Damping:** 0 (No damping, allowing high-frequency content to ring out clearly) 
   - **Send Amount:** Linked 
   - **LinkType:** Decay is linked to the left channel, which could be used to control the reverb tail length dynamically. 
