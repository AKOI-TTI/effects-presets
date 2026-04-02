# Mixxx Custom Effects Presets
[How To Add Effects](#how-to-add-effects)

[Ethereal Ascend Preset](#ethereal-ascend-preset)

[NGC 5194 Preset](#ngc-5194-preset)

[NS-5 Preset](#ns-5-preset)

[NS-7 Preset ⚠️](#ns-7-preset)

[Smooth Transition Preset](#smooth-transition-preset)

[Submerged Preset](#submerged-preset)

[Wah-wahish Preset](#wah-wahish-preset)

## How To Add Effects
For export/import, go to Options menu → Preferences → Effects


## Ethereal Ascend Preset

**Use case:**  This could be used to create a dynamic ethereal and floating effect. Best used for vocals. Twist level knob back and forth to create the effect. 

Recommended:
🎤 - :vox:

Effect Chain Configuration

**Name:** **`Ethereal Ascend`** 

**Mix Mode:** DRY+WET

**Super Parameter Value:** 1 (Fully wet, emphasizing the effects)


**Effects**
1. **Pitch Shift**
- Enabled Parameter Value: 1
- **Parameters:**
   - **Pitch:** Linked (Slightly lowering the pitch to create a more ethereal tone) 
   - **Range:** Linked (Extended range for pitch shifting, allowing for more dramatic changes) 
   - **Semitones Mode:** 1 (Enabled to shift in semitones) 
   - **Formant Preserving:** 0 (Disabled to allow for more dramatic pitch changes) 
   - **LinkType:** Pitch and Range(inverted) are linked, meaning adjusting one will affect the other. This could be used to create a dynamic, smooth transition effect when twisting a knob. 

2. **Reverb**
- Enabled Parameter Value: 1
- **Parameters:** 
   - **Decay:** 0.8 (Long decay time for a haunting echo) 
   - **Bandwidth:** 0.5 (Narrow bandwidth to reduce high-frequency ringing) 
   - **Damping:** 0.7 (High damping to soften the reverb) 
   - **Send Amount:** 0.6 (Moderate send amount to add ambiance) 
   - **LinkType:** None, each parameter is independent. 

3. **Filter**
- Enabled Parameter Value: 1 
- **Parameters:** 
- **LPF (Low Pass Filter):** Linked (Moderate cutoff to add a mellow, ethereal tone) 
   - **Q (Resonance):** 0.5 (Reduced resonance for a smoother filter response) 
   - **HPF (High Pass Filter):** Linked (Low cutoff to remove some low frequencies for clarity) 
   - **LinkType:** LPF is linked to the left channel, and HPF is linked to the right channel, allowing for dynamic control over the cutoff frequencies.


 ## NGC 5194 Preset

**Use case:**  This could be used to create captivating, and immersive galactic wormhole effect, perfect for enhancing transitions or building excitement in your mixes.

Recommended:
🎹 - :synths:
🎸 - :bass:
🥁 - :drums:

🎼 - :Any:

Effect Chain Configuration

**Name:** **`NGC 5194`** 

**Mix Mode:** DRY/WET

**Super Parameter Value:** 1 (Fully wet, emphasizing the effects)

**Effects**
1. **Flanger**
- Enabled Parameter Value: 1 (Maximum intensity for the flanger effect) 
- **Parameters:** 
   - **Speed:** 10 (Faster speed for a more pronounced swirling effect) 
   - **Width:** 8 (Increased width for a wider, more dramatic effect) 
   - **Manual:** 5 (Manual control for fine-tuning) 
   - **Regen:** 0.5 (Moderate regeneration for a sustained effect) 
   - **Mix:** 1 (Full mix to emphasize the flanger effect) 
   - **Triplet:** 0 (No triplet effect) 
   - **Stereo:** 1 (Stereo effect for a more immersive sound) 
   - **LinkType:** Mix is linked to ensure the flanger is fully integrated. 
2. **Echo**
- Enable Parameter Value: 1 
- **Parameters:** 
   - **Delay Time:** 0.2 (Short delay time for a subtle echo) 
   - **Feedback Amount:** 0.5 (Moderate feedback for a sustained echo) 
   - **Pingpong Amount:** 0.5 (Ping pong for a stereo effect) 
   - **Send Amount:** 0.7 (Increased send amount for more pronounced echo) 
   - **Quantize:** 1 (Quantized timing for rhythmic echo) 
   - **Triplet:** 0 (No triplet effect) 
   - **LinkType:** Send Amount is linked to ensure the echo is fully integrated. 
3. **Reverb**
- Enabled Parameter Value: 1
- **Parameters:** 
   - **Decay:** 1 (Longest decay time for a spacious reverb tail) 
   - **Bandwidth:** 1 (Full bandwidth to retain all frequencies) 
   - **Damping:** 0 (No damping to allow high-frequency content to ring out clearly) 
   - **Send Amount:** 1 (Maximum send amount to fully incorporate the reverb effect) 
   - **LinkType:** Decay is linked to the left channel, which could be used to control the reverb tail length dynamically.


 ## NS-5 Preset

**Use case:**  Creates a robotic lite like effect. This could be used to create a rolling, spacey build-up or transition effect.

Recommended:
🎤 - :vox:
🎹 - :synths:
🎸 - :bass:

Effect Chain Configuration

**Name:** **`NS-5`** 

**Mix Mode:** DRY/WET

**Super Parameter Value:** 0.503937 (About halfway wet, balancing the dry signal with the effects)

**Effects**
1. **Echo**
- Enabled Parameter Value: 0.692913
- **Parameters:**
   - **Delay Time:** 0.217103 (Short delay time for a tight, rhythmic repeat)
   - **Feedback Amount:** 0.707946 (High feedback so repeats build and linger)
   - **Pingpong Amount:** 0 (No stereo ping-pong movement)
   - **Send Amount:** Linked (Controls how much echo is applied)
   - **Quantize:** 1 (Quantized timing for rhythmic repeats)
   - **Triplet:** 1 (Triplet timing for a rolling feel)
   - **LinkType:** Send Amount is linked to ensure the echo intensity follows the super knob.
2. **Reverb**
- Enabled Parameter Value: 0.692913
- **Parameters:** 
   - **Decay:** 0.5 (Medium decay time for a spacious tail)
   - **Bandwidth:** 1 (Full bandwidth to retain all frequencies)
   - **Damping:** 0 (No damping to keep the reverb crisp and bright)
   - **Send Amount:** Linked (Controls how much reverb is applied)
   - **LinkType:** Send Amount is linked to ensure the reverb intensity follows the super knob.
3. **Moog Ladder 4 Filter**
- Enabled Parameter Value: 0.692913
- **Parameters:** 
   - **LPF (Low Pass Filter):** Linked (Filter sweep shaping the high end)
   - **Resonance:** 1.2 (Increased resonance for a more pronounced sweep)
   - **HPF (High Pass Filter):** Linked (Filter sweep shaping the low end)
   - **LinkType:** LPF is linked to the left channel, and HPF is linked to the right channel, allowing the super knob to shape both ends of the spectrum.


 ## NS-7 Preset

**Use case:**  Creates a heavy robotic like effect. This could be used to create a rolling, spacey build-up or transition effect.


 NS-7 Preset ⚠️ :caution: (experimental may require lower EQ gains if it gets harsh).

Recommended:
🎤 - :vox:
🎹 - :synths:
🎸 - :bass:

Effect Chain Configuration

**Name:** **`NS-7`** 

**Mix Mode:** DRY/WET

**Super Parameter Value:** 0.692913 (More wet than dry, emphasizing the effect chain)

**Effects**
1. **Echo**
- Enabled Parameter Value: 0.692913
- **Parameters:**
   - **Delay Time:** 0.217103 (Short delay for tight, rhythmic repeats)
   - **Feedback Amount:** 0.707946 (High feedback so repeats build and linger)
   - **Pingpong Amount:** 0 (No stereo ping-pong)
   - **Send Amount:** Linked (Controls how much echo is applied)
   - **Quantize:** 1 (Quantized timing for rhythmic repeats)
   - **Triplet:** 1 (Triplet timing for a rolling feel)
   - **LinkType:** Send Amount is linked to ensure the echo intensity follows the super knob.
2. **Reverb**
- Enabled Parameter Value: 0.692913
- **Parameters:** 
   - **Decay:** 0.5 (Medium decay time for a spacious tail)
   - **Bandwidth:** 1 (Full bandwidth to retain all frequencies)
   - **Damping:** 0 (No damping to keep the reverb crisp and bright)
   - **Send Amount:** Linked (Controls how much reverb is applied)
   - **LinkType:** Send Amount is linked to ensure the reverb intensity follows the super knob.
3. **Echo (Stereo)**
- Enabled Parameter Value: 0.692913
- **Parameters:**
   - **Delay Time:** 0.215555 (Very similar timing for layered repeats)
   - **Feedback Amount:** 0.707946 (High feedback to sustain the echo wash)
   - **Pingpong Amount:** 0.431305 (Adds left-right bounce for wider stereo repeats)
   - **Send Amount:** Linked (Controls how much echo is applied)
   - **Quantize:** 1 (Quantized timing)
   - **Triplet:** 1 (Triplet timing)
   - **LinkType:** Send Amount is linked to ensure this echo layer also follows the super knob.
4. **Moog Ladder 4 Filter**
- Enabled Parameter Value: 0.692913
- **Parameters:** 
   - **LPF (Low Pass Filter):** Linked (Filter sweep shaping the high end)
   - **Resonance:** 1.2 (Increased resonance for a more pronounced sweep)
   - **HPF (High Pass Filter):** Linked (Filter sweep shaping the low end)
   - **LinkType:** LPF is linked to the left channel, and HPF is linked to the right channel, allowing the super knob to shape both ends of the spectrum.


 ## Smooth Transition Preset

**Use case:**  This could be used to create a dynamic, smooth transition effect when twisting level knob. 

Recommended:
🎼 - :Any:

Effect Chain Configuration

**Name:** **`Smooth Transition`** 

**Mix Mode:** DRY/WET

**Super Parameter Value:** 1 (Fully wet, emphasizing the effects)

**Effects**
1. **Bitcrusher**
- Enabled Parameter Value: 1 
- **Parameters:** 
   - **Bit Depth:** Linked
   - **Downsample:** Linked (Extremely low downsample rate, further distorting the sound and creating a smooth, grainy texture) 
   - **LinkType:** Both parameters are linked and inverted.
2. **Moog Ladder 4 Filter**
- Enabled Parameter Value: 1
- **Parameters:** 
   - **LPF (Low Pass Filter):** Linked (Extremely low cutoff, severely cutting off high frequencies and leaving only the lowest bass tones) 
   - **Resonance:** 1.54534 
   - **HPF (High Pass Filter):** 0.0304851 (Low cutoff, removing some very low frequencies but allowing the bass to pass through) 
   - **LinkType:** The LPF is linked and inverted, meaning adjusting it will inversely affect the cutoff frequency, potentially creating a smooth transition from heavy distortion to more open tones. 
3. **Reverb**
- Enabled Parameter Value: 1
- **Parameters:** 
   - **Decay:** Linked 
   - **Bandwidth:** 1 (Full bandwidth, retaining all frequencies in the reverb) 
   - **Damping:** 0 (No damping, allowing high-frequency content to ring out clearly) 
   - **Send Amount:** Linked 
   - **LinkType:** Decay is linked to the left channel, which could be used to control the reverb tail length dynamically.


 ## Submerged Preset

**Use case:**  This could be used to create a captivating underwater or submerged environment, perfect for enhancing transitions or building suspense in your mixes.

Recommended:
🎼 - :Any:

Effect Chain Configuration

**Name:** **`Submerged`** 

**Mix Mode:** DRY+WET

**Super Parameter Value:** 0.866142 (Balanced mix of original and processed signals)

**Effects**
1. **Bitcrusher**
- Enabled Parameter Value: 1 
- **Parameters:** 
   - **Bit Depth:** 10 (Faster speed for a more pronounced swirling effect) 
   - **Downsample:** 1 (Standard downsample rate, maintaining clarity while adding a subtle texture)
   - **LinkType:** Both parameters are linked and inverted, meaning adjusting one will inversely affect the other. This could be used to create a dynamic, smooth transition effect when twisting a knob.
2. **Moog Ladder 4 Filter**
- Enable Parameter Value: 1 
- **Parameters:**
   - **LPF (Low Pass Filter):** 0.5 (Midrange cutoff, allowing mid and low frequencies to pass through)
   - **Resonance** 1.54534 (Increased resonance to emphasize the remaining frequencies and add a rich, resonant tone)
   - **HPF (High Pass Filter):** 0.0003 (Extremely low cutoff, removing very low frequencies but allowing the bass to pass through)
   - **LinkType:** The LPF is linked and inverted, meaning adjusting it will inversely affect the cutoff frequency, potentially creating a smooth transition from heavy distortion to more open tones.
3. **Reverb**
- Enabled Parameter Value: 1
- **Parameters:** 
   - **Decay:** 0 (Shortest decay time, creating a subtle reverb tail)
   - **Bandwidth:** 1 (Full bandwidth to retain all frequencies) 
   - **Damping:** 0 (No damping to allow high-frequency content to ring out clearly) 
   - **Send Amount:** 0 (Minimum send amount, minimally incorporating the reverb effect)
   - **LinkType:** Decay is linked to the left channel, which could be used to control the reverb tail length dynamically. 


 ## Wah-wahish Preset

**Use case:**  This could be used to create a classic wah-wah–like sweep with stereo motion and a light metallic swirl. Twist the super knob to sweep the filter band; autopan adds side-to-side movement and the flanger thickens the midrange.

Recommended:
🎤 - :vox:
🎹 - :synths:
🎸 - :bass:
🥁 - :drums:


Effect Chain Configuration

**Name:** **`Wah-wahish`** 

**Mix Mode:** DRY/WET

**Super Parameter Value:** 0.5 (Half wet, balanced blend of dry and processed signal)

**Effects**
1. **Filter**
- Enabled Parameter Value: 0.5
- **Parameters:**
   - **LPF (Low Pass Filter):** 203.262 (Low cutoff in Hz, darkening the top end; linked for sweep)
   - **Q (Resonance):** 0.707107 (Moderate Q for a smooth, musical peak)
   - **HPF (High Pass Filter):** 21.2197 (Low cutoff in Hz, letting lows through; linked for sweep)
   - **LinkType:** LPF is linked to the left channel, and HPF is linked to the right channel, so the super knob drives a band-pass–style sweep similar to a wah pedal.
2. **Autopan**
- Enabled Parameter Value: 0.5
- **Parameters:**
   - **Period:** 4 (Slower LFO cycle for a gentle left-right motion)
   - **Smoothing:** 0.5 (Moderate smoothing between pan positions)
   - **Width:** 0.298093 (Narrower stereo width for subtle movement)
   - **LinkType:** None on these parameters; pan motion is fixed for a steady rhythmic sway.
3. **Flanger**
- Enabled Parameter Value: 0.5
- **Parameters:**
   - **Speed:** 5.80419 (Moderate modulation rate)
   - **Width:** 4.94002 (Moderate comb-filter sweep width)
   - **Manual:** 4.96847 (Manual offset for the sweep character)
   - **Regen:** 0.25 (Light feedback for a mild metallic emphasis)
   - **Mix:** 0.5 (Half wet; flanger sits under the dry signal)
   - **Triplet:** 0 (Straight timing, not triplet)
   - **LinkType:** None; flanger depth and tone stay stable while filter and pan carry the motion.
