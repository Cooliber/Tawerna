# Warhammer Fantasy Tavern Simulator

A comprehensive tavern simulation set in the Warhammer Fantasy universe, featuring dynamic character interactions, relationship systems, and emergent storytelling.

## Features

### Core Systems
- **17 Unique NPCs** from diverse Warhammer Fantasy factions (Empire, Dwarfs, Elves, Bretonnia, etc.)
- **Dynamic Relationship System** tracking friendships, rivalries, and evolving connections
- **Dice-Based Interactions** with skill checks and random outcomes
- **Tension & Brawl System** with escalating conflicts and tavern fights
- **Random Events** including celebrations, mysterious visitors, and news arrivals
- **Rumor & Gossip System** spreading information between characters

### Character System
Each character features:
- Unique faction-specific abilities and traits
- Detailed backstories and motivations
- Individual personality quirks and dialogue
- Skills system with 15 different abilities
- Dynamic mood and status tracking
- Hidden secrets and personal agendas

### Tavern Features
- **Randomized Tavern Generation** with atmospheric descriptions
- **Service Quality Ratings** affecting prices and atmosphere
- **Dynamic Atmosphere** changing based on events and interactions
- **Capacity Management** with crowding effects
- **Reputation System** affecting tavern standing

### Visualization
- **Interactive Relationship Graph** showing character connections
- **Real-time Updates** as relationships evolve
- **Color-coded Relationships** from hatred to loyalty
- **Multiple Layout Options** for graph visualization

### Session Management
- **Save/Load Functionality** for ongoing campaigns
- **Detailed Session Logs** with interaction history
- **Export Features** for analysis and record-keeping
- **Turn-based Progression** with automatic events

## Installation

### Requirements
- Python 3.7+
- tkinter (usually included with Python)
- matplotlib
- networkx
- numpy

### Setup
1. Clone or download the project
2. Install dependencies:
   ```bash
   pip install matplotlib networkx numpy
   ```
3. Run the simulator:
   ```bash
   python main.py
   ```

## Usage

### Getting Started
1. Launch the application
2. A new tavern will be automatically generated with random characters
3. Use the interface to explore character relationships and trigger interactions

### Main Interface

#### Tavern Panel (Left)
- View tavern information and current status
- Monitor tension levels and atmosphere
- Add/remove characters
- Control simulation progression

#### Character Panel (Right)
- Browse characters currently in the tavern
- View detailed character information
- Examine skills, backstories, and current status
- Manage character actions

#### Central Tabs
- **Relationships**: Interactive graph showing character connections
- **Interactions**: Perform manual interactions between characters
- **Session Log**: View detailed history of all events and interactions

### Interactions

#### Manual Interactions
- Select initiator and target characters
- Choose interaction type (conversation, trade, gambling, etc.)
- View dice roll results and relationship changes

#### Automatic Events
- Random events occur based on tavern tension and atmosphere
- Characters may interact autonomously
- Rumors spread naturally between characters

### Controls

#### Keyboard Shortcuts
- `Ctrl+N`: Generate new tavern
- `Ctrl+S`: Save session
- `Ctrl+O`: Load session
- `Space`: Advance turn
- `F5`: Refresh display

#### Menu Options
- **File**: Save/load sessions, export logs
- **Simulation**: Control turn progression and events
- **View**: Refresh display and character details

## Character Factions

The simulator includes characters from these Warhammer Fantasy factions:

- **Empire**: Humans from the largest nation, featuring soldiers, priests, and craftsmen
- **Dwarfs**: Proud mountain folk with strong traditions and grudges
- **High Elves**: Arrogant but sophisticated elves from Ulthuan
- **Wood Elves**: Wild forest dwellers with nature magic
- **Bretonnia**: Chivalrous knights following the code of honor
- **Halflings**: Peaceful folk focused on food and comfort
- **Tileans**: Mercenary city-state inhabitants
- **Kislev**: Hardy northerners who fight Chaos
- **Norse**: Fierce raiders from the frozen north
- **Arabians**: Exotic traders from distant deserts
- **Cathayans**: Wise scholars from the far east
- **Nipponese**: Honor-bound warriors from distant islands
- **Witch Hunters**: Fanatical purgers of corruption
- **Cultists**: Hidden servants of dark powers (disguised)

## Interaction Types

- **Conversation**: Basic social interaction
- **Trade**: Commercial negotiations
- **Gambling**: Games of chance and skill
- **Information**: Gathering rumors and secrets
- **Intimidation**: Threatening behavior
- **Persuasion**: Convincing others
- **Drinking**: Social drinking activities
- **Storytelling**: Sharing tales and entertainment

## Events

Random events include:
- **Tavern Brawls**: When tension gets too high
- **Celebrations**: Victory announcements, birthdays
- **Mysterious Visitors**: Hooded strangers, witch hunters
- **Merchant Arrivals**: New goods and trade opportunities
- **News Arrivals**: War reports, harvest news
- **Drinking Contests**: Competitive drinking games
- **Storytelling**: Bards and tale-tellers
- **Weather Changes**: Storms trapping patrons inside

## Technical Details

### Architecture
- **Object-Oriented Design** with clear separation of concerns
- **Core Systems**: Character, Tavern, Event, Dice, and Interaction classes
- **GUI Framework**: Tkinter with custom panels and visualization
- **Data Persistence**: Pickle-based save/load system

### File Structure
```
warhammer_tavern_simulator/
├── main.py                 # Application entry point
├── core/                   # Core simulation logic
│   ├── character.py        # Character class and management
│   ├── character_generator.py  # 17 unique NPCs
│   ├── tavern.py          # Tavern class and mechanics
│   ├── tavern_generator.py    # Random tavern generation
│   ├── dice_system.py     # Dice rolling and skill checks
│   ├── event.py           # Events and rumor system
│   ├── enums.py           # Game enumerations
│   └── tavern_simulator.py   # Main simulator class
├── gui/                    # User interface
│   ├── main_window.py     # Main application window
│   ├── character_panel.py # Character information display
│   ├── tavern_panel.py    # Tavern status and controls
│   ├── relationship_graph.py  # Interactive relationship visualization
│   ├── interaction_panel.py   # Interaction management
│   └── log_panel.py       # Session logging and statistics
└── requirements.txt       # Python dependencies
```

## Tips for Play

1. **Watch the Tension**: High tension leads to brawls, which can be exciting but damage relationships
2. **Faction Dynamics**: Some factions naturally get along better than others
3. **Character Secrets**: Each character has hidden motivations that affect their behavior
4. **Rumor Mill**: Pay attention to rumors - they can reveal character secrets
5. **Atmosphere Matters**: Different tavern atmospheres encourage different types of interactions
6. **Save Often**: Interesting scenarios can be saved and revisited later

## Future Enhancements

Potential additions could include:
- More character factions and classes
- Additional interaction types
- Quest and adventure hooks
- Economic simulation
- Weather and seasonal effects
- Character progression and development
- Multiplayer support
- Custom character creation

## License

This project is created for educational and entertainment purposes. Warhammer Fantasy is a trademark of Games Workshop Ltd.

## Contributing

Feel free to suggest improvements, report bugs, or contribute new features. The modular design makes it easy to add new characters, events, or interaction types.

---

*"In the grim darkness of the Old World, there is only... tavern drama!"*
# Tawerna
