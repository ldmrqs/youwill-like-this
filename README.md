# You Will Like This

an AI experimental project where an AI bot gives you music recommendations that **you will actually like** based on your preferences and listening patterns.

## what it does
- input your musical preferences (genres, artists, moods)
- get personalized music recommendations powered by Claude AI
- clean, fast API responses with detailed explanations
- built for experimentation and learning

## tech stack

### backend
- **fastAPI** - modern Python web framework with automatic docs
- **aWS bedrock** - claude AI for intelligent recommendations
- **docker** - containerization for consistent development
- **pydantic** - data validation and serialization
- **terraform** - infrastructure as code for AWS resources

### frontend (coming soon)
- **next.js** + **typeScript** - react framework with type safety
- **tailwind CSS** - utility-first styling
- **vercel** - deployment platform

### infrastructure
- **railway/render** - API deployment
- **AWS IAM** - secure API access to Bedrock
- **AWS cloudWatch** - monitoring and logging

## why this stack?
- **fastAPI**: easier debugging than Lambda, automatic OpenAPI docs
- **bedrock**: direct AI integration without managing models
- **docker**: consistent environments across development and production
- **terraform**: reproducible infrastructure, perfect for portfolios

## getting started

```bash
# Clone the repository
git clone https://github.com/yourusername/you-will-like-this
cd you-will-like-this

# Run with Docker
docker-compose up --build

# Or run locally
pip install -r requirements.txt
uvicorn main:app --reload
```

## API endpoints
- `GET /` - Health check
- `POST /recommend` - Get music recommendations
- `GET /docs` - Interactive API documentation

## future updates
- [ ] TypeScript frontend with modern UI
- [ ] User preference learning and history
- [ ] Spotify/Apple Music integration
- [ ] Advanced filtering and genre exploration
- [ ] Rate limiting and caching

## contributing
this is an experimental project for learning and portfolio purposes. feel free to fork and experiment!