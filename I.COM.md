
{
  "project": {
    "name": "I.COM",
    "version": "1.0.0",
    "type": "AI Game Creation Platform",
    "description": "I.COM is an AI-powered platform for creating, editing, testing and exporting games using natural-language commands.",
    "tagline": "MAKE YOUR GAME USING AI"
  },

  "interface": {
    "style": "modern",
    "theme": {
      "default": "dark",
      "available": [
        "dark",
        "light",
        "system"
      ]
    },

    "main_navigation": [
      "I.COM",
      "Chat",
      "Create Game",
      "My Projects",
      "3D Assets",
      "Settings",
      "Your Account",
      "More"
    ]
  },

  "ai": {
    "name": "RIMO AI",
    "enabled": true,

    "features": [
      "AI Chat",
      "Game Creation",
      "Game Editing",
      "Code Generation",
      "Code Editing",
      "Error Detection",
      "Error Fixing",
      "Character Creation",
      "Enemy Creation",
      "World Creation",
      "Quest Creation",
      "Dialogue Creation",
      "AI Voice Generation",
      "3D Scene Generation",
      "Game Optimization"
    ],

    "natural_language_commands": true,

    "continuous_project_editing": true,

    "example_commands": [
      "Create a horror game",
      "Add a new enemy",
      "Make the enemy faster",
      "Add a new room",
      "Change the lighting",
      "Add a key",
      "Create a locked door",
      "Make the game multiplayer",
      "Fix the errors",
      "Add a character",
      "Change the character clothes"
    ]
  },

  "game_creation": {
    "enabled": true,

    "form": {
      "game_name": {
        "type": "text",
        "required": true
      },

      "game_type": {
        "type": "select",
        "required": true,

        "options": [
          "Horror",
          "Adventure",
          "Action",
          "RPG",
          "Puzzle",
          "Platformer",
          "Simulation",
          "Racing",
          "Strategy",
          "Survival",
          "Multiplayer",
          "Other"
        ]
      },

      "game_description": {
        "type": "textarea",
        "required": true
      }
    },

    "button": {
      "text": "Create Game",
      "action": "create_game"
    }
  },

  "ai_game_builder": {
    "enabled": true,

    "pipeline": [
      "Read User Request",
      "Understand Game Requirements",
      "Create Game Plan",
      "Generate Game Specification",
      "Create World",
      "Create Characters",
      "Create Enemies",
      "Create Objects",
      "Create Gameplay Systems",
      "Generate Code",
      "Validate Code",
      "Build Project",
      "Run Tests",
      "Open Preview"
    ],

    "editing": {
      "enabled": true,
      "edit_existing_projects": true
    }
  },

  "game_engine": {
    "name": "I.COM Engine",
    "enabled": true,

    "supported_game_types": [
      "2D",
      "3D"
    ],

    "systems": [
      "Rendering",
      "Physics",
      "Collision",
      "Lighting",
      "Shadows",
      "Animation",
      "Particles",
      "Audio",
      "AI",
      "Navigation",
      "Inventory",
      "Interactions",
      "Missions",
      "Dialogue",
      "Save System",
      "Multiplayer"
    ]
  },

  "characters": {
    "enabled": true,

    "creator": {
      "enabled": true,

      "options": [
        "Boy",
        "Girl",
        "Custom"
      ],

      "customization": [
        "Name",
        "Age",
        "Face",
        "Hair",
        "Hair Color",
        "Eye Color",
        "Clothes",
        "Shoes",
        "Animations"
      ]
    }
  },

  "enemies": {
    "enabled": true,
    "multiple_enemies": true,

    "creator": {
      "fields": [
        "Image",
        "Name",
        "Age",
        "Description",
        "Movement Behavior",
        "Attack Behavior",
        "Speed",
        "Vision Range",
        "Hearing Range",
        "Patrol Area"
      ]
    },

    "ai_behavior": {
      "natural_language": true,
      "custom_behavior_description": true
    }
  },

  "objects": {
    "enabled": true,

    "interaction_system": {
      "enabled": true,

      "actions": [
        "Pickup",
        "Drop",
        "Open",
        "Close",
        "Push",
        "Pull",
        "Use",
        "Inspect",
        "Activate"
      ],

      "custom_actions": true
    }
  },

  "assets": {
    "enabled": true,

    "supported_formats": [
      ".glb",
      ".gltf",
      ".obj",
      ".fbx",
      ".stl"
    ],

    "actions": [
      "Upload",
      "Import",
      "Preview",
      "Rename",
      "Delete",
      "Add To Project",
      "Edit"
    ],

    "library": {
      "enabled": true,
      "search": true,

      "categories": [
        "Characters",
        "Buildings",
        "Environments",
        "Furniture",
        "Vehicles",
        "Animals",
        "Objects",
        "Animations",
        "Effects"
      ]
    }
  },

  "image_to_3d": {
    "enabled": true,

    "input": "Image",

    "output_formats": [
      ".glb",
      ".gltf"
    ],

    "process": [
      "Analyze Image",
      "Generate 3D Model",
      "Generate Texture",
      "Optimize Model",
      "Preview Model",
      "Add To Project"
    ]
  },

  "voice": {
    "enabled": true,

    "features": [
      "AI Voice Generation",
      "Character Voices",
      "NPC Voices",
      "Enemy Voices",
      "Dialogue Generation"
    ]
  },

  "projects": {
    "name": "My Projects",
    "enabled": true,

    "features": [
      "Create",
      "Open",
      "Save",
      "Rename",
      "Duplicate",
      "Delete",
      "Import",
      "Export",
      "Autosave",
      "Version History"
    ],

    "continue_editing": true
  },

  "preview": {
    "enabled": true,

    "controls": [
      "Play",
      "Pause",
      "Restart",
      "Fullscreen"
    ],

    "debug_console": true
  },

  "debugger": {
    "enabled": true,

    "ai_debugger": {
      "enabled": true,
      "detect_errors": true,
      "explain_errors": true,
      "suggest_fixes": true,
      "auto_fix": true
    },

    "workflow": [
      "Detect Error",
      "Analyze Error",
      "Generate Fix",
      "Apply Fix",
      "Rebuild",
      "Test Again"
    ]
  },

  "multiplayer": {
    "enabled": true,

    "features": [
      "Online Games",
      "Private Rooms",
      "Player Rooms",
      "Join Game",
      "Leave Game",
      "Network Synchronization"
    ]
  },

  "export": {
    "enabled": true,

    "platforms": {
      "android": {
        "enabled": true,
        "format": "APK"
      },

      "web": {
        "enabled": true,
        "format": "Web"
      },

      "windows": {
        "enabled": true,
        "format": "EXE"
      }
    }
  },

  "account": {
    "enabled": true,

    "account_id": {
      "type": "random",
      "digits": 6
    },

    "profile": [
      "Username",
      "Profile Image",
      "Projects"
    ]
  },

  "languages": {
    "enabled": true,

    "available": [
      "Arabic",
      "English",
      "French"
    ],

    "language_switcher": true
  },

  "security": {
    "authentication": true,
    "project_isolation": true,
    "file_validation": true,
    "asset_validation": true,
    "api_key_protection": true
  },

  "core_workflow": {
    "steps": [
      "User describes the game",
      "AI understands the request",
      "AI creates a game plan",
      "AI generates the game specification",
      "AI creates or imports assets",
      "AI generates game code",
      "I.COM builds the project",
      "I.COM runs tests",
      "AI fixes detected errors",
      "User previews the game",
      "User edits the game with commands",
      "User exports the game"
    ]
  },

  "principle": {
    "main_idea": "Users can create and modify games by communicating with AI using natural language.",
    "ai_first_development": true,
    "no_code_required": true,
    "advanced_code_editing": true
  }
}
