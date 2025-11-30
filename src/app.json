import React, { useState } from 'react';
import { ExternalLink, Twitter, Search } from 'lucide-react';

export default function Directory() {
  const [searchTerm, setSearchTerm] = useState('');

  const accounts = [
    {
      category: 'Polymarket Official',
      items: [
        { name: '@Polymarket', description: 'The platform itself. Where your money goes.', x: 'https://x.com/Polymarket', website: null },
        { name: '@PolymarketTrade', description: 'Track profitable traders. Copy smart, not blindly.', x: 'https://x.com/PolymarketTrade', website: null },
        { name: '@PolymarketIntel', description: 'News feed. Sleep on events, lose money.', x: 'https://x.com/PolymarketIntel', website: null },
        { name: '@PolymarketBuild', description: 'New tools drop here.', x: 'https://x.com/PolymarketBuild', website: null }
      ]
    },
    {
      category: 'AI Assistance',
      items: [
        { name: '@Munar_AI', description: 'AI assistants for research and market analysis', x: 'https://x.com/Munar_AI', website: 'https://munar.ai/' },
        { name: '@trypolyagent', description: 'AI assistants for filtering noise', x: 'https://x.com/trypolyagent', website: 'https://trypolyagent.com/' },
        { name: '@polytaleai', description: 'AI assistants for research, market analysis, and filtering noise', x: 'https://x.com/polytaleai', website: null },
        { name: '@polybroapp', description: 'Quantum signals. When it says fade - consider fading.', x: 'https://x.com/polybroapp', website: null },
        { name: '@polysimplr', description: 'Simplified Polymarket interface alternative.', x: 'https://x.com/polysimplr', website: null },
        { name: '@tradefoxai', description: 'Best liquidity across platforms. Spreads matter.', x: 'https://x.com/tradefoxai', website: null },
        { name: '@Ravenai_', description: 'Meta-analysis. For those thinking three steps ahead.', x: 'https://x.com/Ravenai_', website: null },
        { name: '@rainmakerdotfun', description: 'Specifically for sports betting.', x: 'https://x.com/rainmakerdotfun', website: null }
      ]
    },
    {
      category: 'Data & Analytics',
      items: [
        { name: '@PolymarketEco', description: 'Directory of all tools. Bookmark it.', x: 'https://x.com/PolymarketEco', website: null },
        { name: '@layerhub', description: 'Whale and smart money tracking.', x: 'https://x.com/layerhub', website: null },
        { name: '@PolyAlertHub', description: 'Whale and smart money tracking. Know when they move.', x: 'https://x.com/PolyAlertHub', website: null },
        { name: '@pizzintwatch', description: 'Pentagon pizza orders predict military action.', x: 'https://x.com/pizzintwatch', website: null },
        { name: '@poly_data', description: 'Raw data. Do your own analysis.', x: 'https://x.com/poly_data', website: null },
        { name: '@markiumpro', description: 'Raw data. Do your own analysis.', x: 'https://x.com/markiumpro', website: null },
        { name: '@Polysights', description: 'AI against revenge trading.', x: 'https://x.com/Polysights', website: null },
        { name: '@hash_dive', description: 'Smart Scores = statistical edge. Check before big trades.', x: 'https://x.com/hash_dive', website: null },
        { name: '@NevuaMarkets', description: 'Instant alerts. Set it up or miss opportunities.', x: 'https://x.com/NevuaMarkets', website: null },
        { name: '@polyfactual', description: 'Weekly streams and complete guide. Free alpha for beginners.', x: 'https://x.com/polyfactual', website: null },
        { name: '@Polynoob_', description: 'Weekly streams and complete guide. Free alpha for beginners.', x: 'https://x.com/Polynoob_', website: null },
        { name: '@polyscope_', description: 'Free monitoring dashboard.', x: 'https://x.com/polyscope_', website: null },
        { name: '@predictionindex', description: 'Market aggregation beyond Polymarket.', x: 'https://x.com/predictionindex', website: null },
        { name: '@Predictifybot', description: 'Market aggregation beyond Polymarket. More opportunities.', x: 'https://x.com/Predictifybot', website: null },
        { name: '@MentionMetrix', description: 'Market aggregation beyond Polymarket. More opportunities.', x: 'https://x.com/MentionMetrix', website: null },
        { name: '@PredictFolio', description: 'Real-time portfolio tracking.', x: 'https://x.com/PredictFolio', website: null }
      ]
    },
    {
      category: 'Trading Assistance',
      items: [
        { name: '@OstiumLabs', description: 'Long/short TradFi assets onchain with leverage.', x: 'https://x.com/OstiumLabs', website: null },
        { name: '@fliprbot', description: 'Leverage for prediction markets. Careful, liquidations are real.', x: 'https://x.com/fliprbot', website: null },
        { name: '@tryokbet', description: 'Telegram and Twitter bots. Trade when you\'re not at your desk.', x: 'https://x.com/tryokbet', website: null },
        { name: '@PolyxBot', description: 'Telegram and Twitter bots. Trade when you\'re not at your desk.', x: 'https://x.com/PolyxBot', website: null },
        { name: '@bankrbot', description: 'Telegram and Twitter bots. Trade when you\'re not at your desk.', x: 'https://x.com/bankrbot', website: null },
        { name: '@polymtrade', description: 'Mobile terminals. Trade from anywhere.', x: 'https://x.com/polymtrade', website: null },
        { name: '@polyswipe_app', description: 'Mobile terminals. Trade from anywhere.', x: 'https://x.com/polyswipe_app', website: null },
        { name: '@BetlyTrade', description: 'Mobile terminals. Trade from anywhere.', x: 'https://x.com/BetlyTrade', website: null },
        { name: '@polyburg', description: 'Catches signals others miss. Contrarian positions.', x: 'https://x.com/polyburg', website: null },
        { name: '@sportstensor', description: 'Collective intelligence for sports.', x: 'https://x.com/sportstensor', website: null },
        { name: '@StandDOTtrade', description: 'Advanced terminals. Everything in one place.', x: 'https://x.com/StandDOTtrade', website: null },
        { name: '@auradotmoney', description: 'Advanced terminals. Everything in one place.', x: 'https://x.com/auradotmoney', website: null }
      ]
    },
    {
      category: 'Communities',
      items: [
        { name: '@zscdao', description: 'Real traders. Network here.', x: 'https://x.com/zscdao', website: null },
        { name: '@predictionarc', description: 'For beginners. Start here. Biggest Community, supported by Poly.', x: 'https://x.com/predictionarc', website: null }
      ]
    }
  ];

  const filtered = accounts.map(section => ({
    ...section,
    items: section.items.filter(item =>
      item.name.toLowerCase().includes(searchTerm.toLowerCase()) ||
      item.description.toLowerCase().includes(searchTerm.toLowerCase())
    )
  })).filter(section => section.items.length > 0);

  return (
    <div className="min-h-screen bg-gradient-to-br from-slate-900 via-slate-800 to-slate-900 p-6">
      <div className="max-w-4xl mx-auto">
        {/* Header */}
        <div className="mb-12">
          <h1 className="text-5xl font-bold text-white mb-2">Polymarket Directory</h1>
          <p className="text-slate-400 text-lg">Official accounts & AI tools for prediction markets</p>
        </div>

        {/* Search */}
        <div className="relative mb-8">
          <Search className="absolute left-4 top-1/2 -translate-y-1/2 text-slate-400" size={20} />
          <input
            type="text"
            placeholder="Search accounts..."
            value={searchTerm}
            onChange={(e) => setSearchTerm(e.target.value)}
            className="w-full pl-12 pr-4 py-3 bg-slate-700 border border-slate-600 rounded-lg text-white placeholder-slate-400 focus:outline-none focus:border-blue-500 focus:ring-2 focus:ring-blue-500/20"
          />
        </div>

        {/* Results */}
        {filtered.length === 0 ? (
          <div className="text-center text-slate-400 py-12">
            <p>No accounts found matching your search.</p>
          </div>
        ) : (
          filtered.map((section, idx) => (
            <div key={idx} className="mb-10">
              <h2 className="text-2xl font-bold text-blue-400 mb-4">{section.category}</h2>
              <div className="space-y-4">
                {section.items.map((item, itemIdx) => (
                  <div
                    key={itemIdx}
                    className="bg-slate-800 border border-slate-700 rounded-lg p-5 hover:border-blue-500 transition-colors"
                  >
                    <div className="flex items-start justify-between mb-2">
                      <h3 className="text-xl font-semibold text-white">{item.name}</h3>
                    </div>
                    <p className="text-slate-300 mb-4">{item.description}</p>
                    <div className="flex gap-3 flex-wrap">
                      {item.x && (
                        <a
                          href={item.x}
                          target="_blank"
                          rel="noopener noreferrer"
                          className="inline-flex items-center gap-2 px-4 py-2 bg-blue-600 hover:bg-blue-700 text-white rounded-lg transition-colors"
                        >
                          <Twitter size={18} />
                          X Profile
                          <ExternalLink size={16} />
                        </a>
                      )}
                      {item.website && (
                        <a
                          href={item.website}
                          target="_blank"
                          rel="noopener noreferrer"
                          className="inline-flex items-center gap-2 px-4 py-2 bg-slate-700 hover:bg-slate-600 text-white rounded-lg transition-colors"
                        >
                          Website
                          <ExternalLink size={16} />
                        </a>
                      )}
                    </div>
                  </div>
                ))}
              </div>
            </div>
          ))
        )}
      </div>
    </div>
  );
}