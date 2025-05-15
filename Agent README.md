# Agent Readme
# Airbnb Assistant Agent

**Description**: This AI Agent provides comprehensive access to Airbnb listings and detailed property information through conversational interaction. It connects directly to real-time Airbnb data to deliver reliable search results and in-depth property details that general language models cannot accurately provide. Simply ask natural questions like "Find Airbnb rentals in Barcelona for next week" or "Show me details for listing ID 12345" to receive structured, detailed information about available accommodations. The agent combines AI-powered natural language understanding with direct access to Airbnb listing data for travel planning and accommodation research.

**Input Data Model**
```python
class AirbnbRequest(Model):
    request_type: str  # "search" or "details"
    parameters: dict
```
**Output Data Model**
```python
class AirbnbResponse(Model):
    results: str
```


