# Neo4j AI Agent Template

🤖 **An intelligent database assistant that converts natural language questions into Neo4j Cypher queries**

## 🎯 What This Does

Transform your Neo4j database interactions from complex query writing to simple conversations:

- **Before**: `MATCH (c:Customer)-[:HAS_INVOICE]->(i:Invoice) WHERE i.dueDate < date() RETURN c.name`
- **After**: "Show me customers with overdue invoices"

## 🚀 Quick Start

1. **Prerequisites:**
   - Google Cloud Project with billing enabled
   - Neo4j database (Aura or self-hosted)
   - 5-15 minutes for setup

2. **Get Started:**
   - Download `Neo4j_Agent.ipynb` 
   - Upload to Google Colab
   - Follow the step-by-step guide
   - Enter your credentials when prompted

3. **Deploy:**
   - Test locally first
   - Deploy to Google Cloud
   - Share with your team

## 📋 What You'll Get

✅ **Natural Language Database Queries** - Ask questions in plain English  
✅ **Automatic Schema Discovery** - Agent learns your database structure  
✅ **Cloud Deployment** - Accessible to your entire team  
✅ **Read-Only Security** - Safe exploration without data modification  
✅ **Interactive Setup** - Guided configuration with validation  
✅ **Production Ready** - Scalable deployment to Google Cloud  

## 🔧 Technology Stack

- **Neo4j** - Graph database
- **Google Vertex AI** - AI platform
- **Google ADK** - Agent Development Kit  
- **Gemini 2.5** - Latest language model
- **Python** - Implementation language

## 📝 Implementation Phases

The notebook guides you through 4 complete phases:

### Phase 1: Environment Setup 🔧
- Install required packages and dependencies
- Authenticate with Google Cloud
- Interactive credential configuration with validation
- Project and resource verification

### Phase 2: Local Development & Testing 🧪
- Create and configure the AI agent
- Implement Neo4j connection tools
- Real-time testing with your database
- Schema discovery and query execution

### Phase 3: Deployment Preparation 🎯
- Prepare cloud deployment configuration
- Set up environment variables securely
- Validate deployment readiness
- Configure resource specifications

### Phase 4: Cloud Deployment ☁️
- Deploy to Vertex AI Agent Engine
- Test deployed functionality in the cloud
- Verify production access and connectivity
- Performance and reliability checks

### Phase 5: Agentspace Registration 🏢
- Register agent with organizational Agentspace
- Configure discovery and access permissions
- Set up agent gallery integration
- Enable team collaboration features

### Phase 6: Management & Cleanup 🛠️
- Test direct agent engine connections
- Delete agent registrations when needed
- Troubleshoot deployment issues
- Monitor and maintain agent performance

## 🎓 Perfect For Learning

This template is designed for developers who want to learn:

- **AI Agent Development** - Hands-on experience with Google ADK
- **Graph Database Integration** - Real-world Neo4j connections
- **Cloud Deployment** - Production-ready Google Cloud setup
- **Natural Language Processing** - Converting speech to database queries

## 📚 Resources & Learning

- **[Google ADK Documentation](https://google.github.io/adk-docs/)** - Official agent development guide
- **[Neo4j Cypher Manual](https://neo4j.com/docs/cypher-manual/)** - Complete query language reference
- **[Vertex AI Agent Engine](https://google.github.io/adk-docs/deploy/agent-engine/)** - Cloud deployment guide
- **[Neo4j Aura](https://neo4j.com/cloud/aura/)** - Managed Neo4j cloud service


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

*Created with ❤️ for non developers who want to make databases more accessible through natural language.*
