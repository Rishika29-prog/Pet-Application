import React, { useState } from "react";
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";

// Husband's name constant
const HUSBAND_NAME = "Ramu";

// Updated Gift Clues
const GIFT_CLUES = [
  "🎁 Gift #1 is waiting under the sofa!",
  "🎁 Gift #2 is chilling inside the fridge.",
  "🎁 Gift #3 hides where you keep your laptop.",
  "🎁 Gift #4 is inside the TV wardrobe, right drawer.",
  "🎁 Gift #5: Check the kitchen rack with glass window."
];

const GAMES = [
  {
    question: "❤️ Guess my favorite color?",
    answer: "red",
  },
  {
    question: "🍫 Which chocolate do I love the most?",
    answer: "dairy milk",
  },
  {
    question: "🌍 Where do I dream of traveling with you?",
    answer: "paris",
  },
];

export default function App() {
  const [step, setStep] = useState(0);
  const [input, setInput] = useState("");
  const [message, setMessage] = useState("");
  const [giftIndex, setGiftIndex] = useState(0);

  const handleAnswer = () => {
    if (input.toLowerCase().trim() === GAMES[step - 1].answer) {
      setMessage("✅ Correct! Here's your gift clue:");
      setGiftIndex(step - 1);
    } else {
      setMessage("❌ Wrong answer! Try again ❤️");
    }
    setInput("");
  };

  const handleSkip = () => {
    setMessage("⏩ Skipped! Here's the solution and your gift clue:");
    setGiftIndex(step - 1);
  };

  return (
    <div className="min-h-screen flex flex-col items-center justify-center bg-gradient-to-br from-pink-200 to-yellow-100 p-6">
      <motion.h1
        initial={{ scale: 0 }}
        animate={{ scale: 1 }}
        transition={{ type: "spring", stiffness: 120 }}
        className="text-4xl font-bold text-pink-600 mb-6"
      >
        🎉 Happy Birthday {HUSBAND_NAME}! 🎉
      </motion.h1>

      {step === 0 ? (
        <Card className="max-w-lg shadow-xl rounded-2xl">
          <CardContent className="p-6 space-y-4 text-center">
            <p>
              Thank you for poruthufying my paithiyakara thanams and you also
              made me feel special. For such a person, I want to make you feel
              very very very special. I swear I'll do my best efforts to make
              you feel that way everyday. You are my comfort zone. You are my
              soul mate. Love you more than anything my Gundu Gundaaaa Gundaaa.
              ❤️oru chinna game poduvoma?🗝️🎁
            </p>
            <Button onClick={() => setStep(1)}>Start Game 👉</Button>
          </CardContent>
        </Card>
      ) : step <= GAMES.length ? (
        <Card className="max-w-lg shadow-xl rounded-2xl">
          <CardContent className="p-6 space-y-4 text-center">
            <h2 className="text-xl font-semibold">{GAMES[step - 1].question}</h2>
            <input
              type="text"
              className="w-full border rounded-lg p-2"
              placeholder="Your answer..."
              value={input}
              onChange={(e) => setInput(e.target.value)}
            />
            <div className="flex gap-4 justify-center">
              <Button onClick={handleAnswer}>Submit</Button>
              <Button variant="secondary" onClick={handleSkip}>
                Skip ⏩
              </Button>
            </div>
            {message && (
              <motion.div
                initial={{ opacity: 0 }}
                animate={{ opacity: 1 }}
                className="mt-4 text-pink-600"
              >
                <p>{message}</p>
                {giftIndex >= 0 && GIFT_CLUES[giftIndex] && (
                  <p className="font-bold mt-2">{GIFT_CLUES[giftIndex]}</p>
                )}
              </motion.div>
            )}
            <Button className="mt-4" onClick={() => setStep(step + 1)}>
              Next ➡️
            </Button>
          </CardContent>
        </Card>
      ) : (
        <motion.div
          initial={{ opacity: 0 }}
          animate={{ opacity: 1 }}
          className="text-center"
        >
          <h2 className="text-2xl font-bold text-green-600">
            🎊 Yay! You completed all the games, {HUSBAND_NAME}! 🎊
          </h2>
          <p className="mt-4">Now go find all your gifts! 💝</p>
        </motion.div>
      )}
    </div>
  );
}
