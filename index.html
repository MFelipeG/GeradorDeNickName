import { useState } from "react"; import { Button } from "@/components/ui/button"; import { motion } from "framer-motion"; import { Copy, DollarSign } from "lucide-react";

const simpleNames = [ "ShadowKiller", "FireLegend", "GhostRider", "ThunderStrike", "DarkPhoenix", "WarriorX", "SniperWolf", "NightHunter", "DragonSoul", "FuryMaster" ];

const specialNames = new Set(); const emblems = [ "🔥", "⚡", "💀", "🐉", "👑", "🎯", "🛡️", "⚔️", "👾", "🏆" ]; const prices = ["$1 USD", "R$5 BRL"];

const generateUniqueSpecialName = () => { let uniqueName; do { uniqueName = ${emblems[Math.floor(Math.random() * emblems.length)]}  + ${Math.random().toString(36).substring(2, 10).toUpperCase()}  + ${emblems[Math.floor(Math.random() * emblems.length)]}; } while (specialNames.has(uniqueName)); specialNames.add(uniqueName); return uniqueName; };

export default function GameNameGenerator() { const [generatedName, setGeneratedName] = useState(""); const [category, setCategory] = useState("simple"); const [price, setPrice] = useState("$");

const generateName = () => { if (category === "simple") { const randomName = simpleNames[Math.floor(Math.random() * simpleNames.length)]; const randomEmblem = emblems[Math.floor(Math.random() * emblems.length)]; setGeneratedName(${randomEmblem} ${randomName} ${randomEmblem}); setPrice("Grátis"); } else { const specialName = generateUniqueSpecialName(); setGeneratedName(specialName); setPrice(prices[Math.floor(Math.random() * prices.length)]); } };

const copyToClipboard = () => { navigator.clipboard.writeText(generatedName); };

return ( <div className="flex flex-col items-center justify-center min-h-screen bg-gray-900 text-white p-4"> <h1 className="text-3xl font-bold mb-4">Gerador de Nomes para Jogos</h1> <div className="flex gap-4 mb-4"> <Button onClick={() => setCategory("simple")} className={category === "simple" ? "bg-green-500" : "bg-gray-700"}>Simples</Button> <Button onClick={() => setCategory("special")} className={category === "special" ? "bg-purple-500" : "bg-gray-700"}>Especiais</Button> </div> <Button onClick={generateName} className="bg-blue-500 hover:bg-blue-700 text-white px-4 py-2 rounded-lg mb-4"> Gerar Nome </Button> {generatedName && ( <motion.div initial={{ opacity: 0, y: -10 }} animate={{ opacity: 1, y: 0 }} className="text-2xl font-semibold bg-gray-800 p-3 rounded-lg flex flex-col items-center gap-2" > <span>{generatedName}</span> <div className="flex items-center gap-2 text-yellow-400"> <DollarSign /> {price} </div> <Copy className="cursor-pointer" onClick={copyToClipboard} /> </motion.div> )} </div> ); }

