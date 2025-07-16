# Fresh Air Breathing Visualizer - Design Document

## Core Concept
A multi-modal breathing guidance tool that uses visual rhythms and ambient sound to train and maintain various breathing patterns for different life contexts.

## Expanded Topic Sections

### Awareness Retention
- **Visual Memory Anchors**: Distinctive visual patterns for each breathing technique that persist in memory
- **Peripheral Vision Training**: Subtle animations in screen corners for ambient awareness
- **Progress Tracking**: Visual history of breathing sessions to reinforce habit formation
- **Transition Cues**: Gentle visual/audio prompts when switching between breathing patterns

### Focus
- **Attention Anchoring**: Central focal point with expanding/contracting elements
- **Distraction Filtering**: Option to dim/blur background elements
- **Cognitive Load Indicators**: Visual complexity that adjusts based on user's focus level
- **Task-Specific Modes**: Different visual patterns for work focus vs. meditation focus

### Relaxation
- **Biophilic Patterns**: Nature-inspired visuals (waves, clouds, fractals)
- **Color Temperature Shifts**: Warm tones for evening, cool for alertness
- **Progressive Muscle Relaxation Cues**: Visual body scan guidance
- **Sleep Preparation Mode**: Gradually dimming visuals with longer exhale phases

### Breath Control
- **Precision Timing**: Millisecond-accurate visual cues for specific ratios
- **Resistance Training**: Visual feedback for breath strength/volume (speculative feature)
- **Pattern Library**: Pre-set and custom breathing patterns (4-7-8, box breathing, etc.)
- **Adaptation Feedback**: Visual rewards for maintaining rhythm

## Key Features

### 1. Visual Modes
- **Central Orb**: Classic expanding/contracting sphere
- **Wave Patterns**: Sinusoidal flows across screen
- **Particle Systems**: Breathing-synchronized particle movements
- **Geometric Transforms**: Sacred geometry morphing with breath
- **Nature Simulations**: Trees swaying, water rippling, clouds forming

### 2. Sound Design
- **Binaural Beats**: Frequency-matched to breathing phases
- **Nature Sounds**: Ocean waves, forest ambience, rain
- **Harmonic Tones**: Musical intervals that guide breath depth
- **White/Pink/Brown Noise**: Options for focus enhancement
- **Silence Mode**: Visual-only for noise-sensitive environments

### 3. Breathing Patterns
- **Regular Flow**: 4-4-4 balanced breathing
- **Stress Response**: 4-2-6 calming pattern for acute stress
- **Energy Boost**: 6-2-2 for alertness
- **Box Breathing**: 4-4-4-4 for focus
- **Custom Patterns**: User-defined ratios

### 4. Conditioning Features
- **Haptic Feedback**: Phone vibration patterns (when applicable)
- **Audio Fade**: Gradually reduce audio cues to train independence
- **Visual Minimization**: Progressive reduction of visual intensity
- **Reminder System**: Gentle prompts for breathing check-ins

### 5. Peripheral Modes
- **Corner Beacon**: Small pulsing indicator in screen corner
- **Browser Extension Mode**: Thin bar at top/bottom of screen
- **Transparency Mode**: Semi-transparent overlay for multitasking
- **Widget Mode**: Minimal floating element

## Technical Considerations

### Rendering Technologies
- **Canvas 2D**: For simple geometric animations and particle systems
- **WebGL**: For complex 3D visualizations and shader effects
- **SVG**: For crisp vector animations and morphing shapes
- **CSS Animations**: For UI elements and simple transitions
- **Web Audio API**: For dynamic sound generation and binaural beats

### Performance Optimization
- **RequestAnimationFrame**: Smooth 60fps animations
- **GPU Acceleration**: Offload complex calculations to shaders
- **Progressive Enhancement**: Fallbacks for older devices
- **Battery Awareness**: Reduced effects on low battery

### Accessibility
- **High Contrast Mode**: For visual impairments
- **Keyboard Navigation**: Full keyboard control
- **Screen Reader Support**: Audio descriptions of breathing phases
- **Colorblind Modes**: Alternative color schemes

## User Experience Flow

1. **Onboarding**: Quick tutorial showing basic controls and patterns
2. **Pattern Selection**: Choose from presets or create custom
3. **Environment Setup**: Select visual theme and sound profile
4. **Session Start**: Gradual fade-in to breathing rhythm
5. **Active Session**: Real-time visual/audio guidance
6. **Session End**: Gentle fade-out with session summary

## Limitations & Constraints

### Browser Limitations
- No direct biometric input (heart rate, breath detection)
- Limited background processing for reminders
- Web Audio API constraints on mobile browsers
- No native OS integration for notifications

### Scope Boundaries
- Not a medical device or treatment
- Cannot detect actual breathing (visual guidance only)
- Limited offline functionality
- No social features or data sharing

## Self-Conditioning Strategy

The tool employs graduated independence through:
1. **Phase 1**: Full visual/audio guidance
2. **Phase 2**: Reduced visual intensity, maintaining audio
3. **Phase 3**: Minimal visual cues, ambient sound only
4. **Phase 4**: Peripheral reminders only
5. **Phase 5**: User practices independently with occasional check-ins

This progressive reduction helps users internalize breathing rhythms for use without the tool.