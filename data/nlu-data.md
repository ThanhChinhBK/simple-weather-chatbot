{
  "rasa_nlu_data": {
    "common_examples": [
      {
        "text": "hello",
        "intent": "greet",
        "entities": []
      },
      {
        "text": "hi",
        "intent": "greet",
        "entities": []
      },
      {"text": "I am thinh kute",
      "intent":"my_name_is",
      "entities" :           [{
            "start": 5,
            "end": 15,
            "value": "thinh kute",
            "entity": "per"
          }]
      },
      {"text": "I am chinh",
      "intent":"my_name_is",
      "entities" :           [{
            "start": 5,
            "end": 11,
            "value": "chinh",
            "entity": "per"
          }]
      },
                {"text": "I am thinh",
      "intent":"my_name_is",
      "entities" :           [{
            "start": 5,
            "end": 11,
            "value": "thinh",
            "entity": "per"
          }]
      },
      {
        "text": "How's the weather today in Berlin?",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 27,
            "end": 33,
            "value": "Berlin",
            "entity": "location"
          }
        ]
      },
      {
        "text": "What's the weather today in Berlin?",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 27,
            "end": 33,
            "value": "Berlin",
            "entity": "location"
          }
        ]
      },
      {
        "text": "What is the weather today in Berlin?",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 29,
            "end": 36,
            "value": "Berlin",
            "entity": "location"
          }
        ]
      },
            {
        "text": "What 's the weather today in Berlin?",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 29,
            "end": 36,
            "value": "Berlin",
            "entity": "location"
          }
        ]
      },
            {
        "text": "What is weather today in Berlin?",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 24,
            "end": 31,
            "value": "Berlin",
            "entity": "location"
          }
        ]
      },
                  {
        "text": "What 's weather today in Berlin?",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 24,
            "end": 31,
            "value": "Berlin",
            "entity": "location"
          }
        ]
      },
      {
        "text": "hola",
        "intent": "greet",
        "entities": []
      },
      {
        "text": "hello, how are you today?",
        "intent": "greet",
        "entities": []
      },
      {
        "text": "yo",
        "intent": "greet",
        "entities": []
      },
      {
        "text": "How's weather in Stuttgart today?",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 17,
            "end": 26,
            "value": "Stuttgart",
            "entity": "location"
          }
        ]
      },
      {
        "text": "What's going on Berlin today?",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 16,
            "end": 22,
            "value": "Berlin",
            "entity": "location"
          }
        ]
      },
      {
        "text": "bye",
        "intent": "goodbye",
        "entities": []
      },
      {
        "text": "see ya",
        "intent": "goodbye",
        "entities": []
      },
      {
        "text": "cya",
        "intent": "goodbye",
        "entities": []
      },
      {
        "text": "How's the weather today?",
        "intent": "ask_weather",
        "entities": []
      },
      {
        "text": "What's today's weather?",
        "intent": "ask_weather",
        "entities": []
      },
      {
        "text": "How is it out there today?",
        "intent": "ask_weather",
        "entities": []
      },
      {
        "text": "In Prague",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 3,
            "end": 9,
            "value": "Prague",
            "entity": "location"
          }
        ]
      },
      {
        "text": "at Prague",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 3,
            "end": 9,
            "value": "Prague",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Budapest",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 0,
            "end": 7,
            "value": "Budapest",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Hanoi",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 0,
            "end": 5,
            "value": "Hanoi",
            "entity": "location"
          }
        ]
      },    
      {
        "text": "What is the temp in Stuttgart?",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 20,
            "end": 29,
            "value": "Stuttgart",
            "entity": "location"
          }
        ]
      },
      {
        "text": "How is the temperature in Amsterdam now?",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 26,
            "end": 35,
            "value": "Amsterdam",
            "entity": "location"
          }
        ]
      },
      {
        "text": "What is temperature in New York now?",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 23,
            "end": 31,
            "value": "New York",
            "entity": "location"
          }
        ]
      },
      {
        "text": "How's current temperature in Moscow now?",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 29,
            "end": 35,
            "value": "Moscow",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Tell me temperature in Helsinki now.",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 23,
            "end": 31,
            "value": "Helsinki",
            "entity": "location"
          }
        ]
      },
      {
        "text": "What's overall weather today?",
        "intent": "ask_weather",
        "entities": []
      },
      {
        "text": "Tell me today's weather",
        "intent": "ask_weather",
        "entities": []
      },
      {
        "text": "See you later",
        "intent": "goodbye",
        "entities": []
      },
      {
        "text": "Good bye",
        "intent": "goodbye",
        "entities": []
      },
      {
        "text": "Nancy",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 0,
            "end": 5,
            "value": "Nancy",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Tell me weather of Dresden",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 19,
            "end": 26,
            "value": "Dresden",
            "entity": "location"
          }
        ]
      },
      {
        "text": "What about in Rome today?",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 14,
            "end": 18,
            "value": "Rome",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Show me weather of Venice",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 19,
            "end": 25,
            "value": "Venice",
            "entity": "location"
          }
        ]
      },
      {
        "text": "How about weather in Italy",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 21,
            "end": 26,
            "value": "Italy",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Sorry, in Vatican",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 10,
            "end": 17,
            "value": "Vatican",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Uhh, how about in Bulgaria?",
        "intent": "ask_weather_location",
        "entities": [
          {
            "start": 18,
            "end": 26,
            "value": "Bulgaria",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Tell the temperature in Caen",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 24,
            "end": 28,
            "value": "Caen",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Temp in Calgary?",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 8,
            "end": 15,
            "value": "Calgary",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Current temperature in London?",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 23,
            "end": 29,
            "value": "London",
            "entity": "location"
          }
        ]
      },
      {
        "text": "Show the temp in UK?",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 17,
            "end": 19,
            "value": "UK",
            "entity": "location"
          }
        ]
      },
      {
        "text": "what about today's temperature in Munich?",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 34,
            "end": 40,
            "value": "Munich",
            "entity": "location"
          }
        ]
      },
      {
        "text": "hey, what's current temp in budapest?",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 28,
            "end": 36,
            "value": "budapest",
            "entity": "location"
          }
        ]
      },
      {
        "text": "show me current canada temperature",
        "intent": "ask_temperature",
        "entities": [
          {
            "start": 16,
            "end": 22,
            "value": "canada",
            "entity": "location"
          }
        ]
      },
      {
        "text": "hiya",
        "intent": "greet",
        "entities": []
      },
      {
        "text": "hello there",
        "intent": "greet",
        "entities": []
      },
      {
        "text": "Umm, hey",
        "intent": "greet",
        "entities": []
      },
      {
        "text": "bye then",
        "intent": "goodbye",
        "entities": []
      },
      {
        "text": "okay, thanks, cya ",
        "intent": "goodbye",
        "entities": []
      }
    ]
  }
}
