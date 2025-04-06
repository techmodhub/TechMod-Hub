import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Instagram } from "lucide-react";

export default function Home() { return ( <main className="min-h-screen bg-black text-white p-4"> <header className="text-center py-6"> <h1 className="text-4xl font-bold text-green-500">TechMod Hub</h1> <p className="text-red-500">Presented by Prashant Pandey</p> </header>

<section className="grid md:grid-cols-2 gap-6">
    <Card className="bg-zinc-900 border-green-500 border shadow-lg">
      <CardContent className="p-4">
        <h2 className="text-xl font-semibold text-green-400 mb-2">Bike Modifications</h2>
        <p>Latest and coolest bike mods, especially monster-themed customizations.</p>
      </CardContent>
    </Card>

    <Card className="bg-zinc-900 border-red-500 border shadow-lg">
      <CardContent className="p-4">
        <h2 className="text-xl font-semibold text-red-400 mb-2">Mobile Updates</h2>
        <p>Stay updated with the newest mobile technology, apps, and tricks.</p>
      </CardContent>
    </Card>
  </section>

  <footer className="mt-10 text-center text-sm text-zinc-400">
    <p>Connect on Instagram</p>
    <a
      href="https://www.instagram.com/smartiboyprashant"
      target="_blank"
      className="inline-flex items-center gap-2 text-green-400 hover:underline"
    >
      <Instagram size={18} /> @smartiboyprashant
    </a>
    <p className="mt-2 text-xs text-zinc-600">#PraKajal</p>
  </footer>
</main>

); }

