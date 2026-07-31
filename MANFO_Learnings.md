# MANFO Project: Actual Learnings & Experiences

## Technical Skills Gained

### Full-Stack Development
- **React Native**: Component/Props/State patterns, iOS/Android cross-platform builds, navigation libraries
- **Node.js + Express.js**: Backend server architecture, API endpoint design, health check endpoints
- **Firebase**: Firestore NoSQL data modeling, Storage image upload, Auth authentication, Admin SDK
- **Google Maps API**: Reverse geocoding, custom markers, location-based filtering

### AI/ML Integration
- **Gemini 2.5/3.1 Flash Lite**: Multimodal image analysis, structured JSON output extraction
- **Whisper (whisper-large-v3)**: Voice-to-text transcription with audio preprocessing
- **Llama models**: Text summarization and analysis
- **Prompt engineering**: Forcing consistent JSON format, defensive parsing for edge cases

### DevOps & Deployment
- **Google Cloud Run**: Serverless container deployment, port optimization, resource management
- **Fluent-ffmpeg**: Media format conversion (OGA → MP3)
- **Container-based deployment**: Docker workflow for production

### Security & Access Control
- **RBAC (Role-Based Access Control)**: User vs Emergency Unit permissions
- **Firebase security rules**: Balancing public report accessibility with authenticated access
- **ZXCVBN**: Password strength measurement algorithm
- **Privacy Policy**: Store submission requirements

---

## Engineering Practices

| Area                    | What You Learned                                                           |
| ----------------------- | -------------------------------------------------------------------------- |
| **Git/GitHub**          | Branch strategy (`feature/` naming), PR review process, commit conventions |
| **Data Design**         | NoSQL denormalization for query performance, composite indexes             |
| **State Machine (FSM)** | Managing async multi-channel conversations                                 |
| **Defensive Coding**    | Handling unexpected AI responses, edge cases, error recovery               |
| **Cost Optimization**   | Google Cloud cost monitoring, API call minimization, response caching      |

---

## Key Insights

1. **Backend development core**: "The key is how you design and manage data" — data structure affects query performance and scalability

2. **AI integration reality**: Generating consistent JSON from LLM requires much more careful prompt design than expected; defensive parsing is essential

3. **Integration engineering**: Combining multiple platforms (Telegram SDK, LINE SDK, Firebase, Gemini) into one cohesive system — "the beauty of integration"

4. **UX vs Technology gap**: "A well-functioning system and a well-used system are fundamentally different challenges"

5. **Multilingual impact**: Supporting Korean, English, and Burmese showed how technology can serve disaster-affected populations without language barriers

6. **Communication matters**: Presenting technical work clearly is as important as building it

---

## Project Deliverables Completed

- ✅ Telegram Bot (AI-powered disaster reporting)
- ✅ LINE Bot (multi-channel support)
- ✅ Mobile App (React Native, iOS + Android)
- ✅ Emergency Unit Dashboard (admin panel)
- ✅ Real-time incident map with filtering
- ✅ 3-language support (Korean/English/Burmese)
- ✅ App Store + Play Store deployment

---

