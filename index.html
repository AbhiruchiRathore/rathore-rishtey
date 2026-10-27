import React, { useState, useMemo } from 'react';
import { 
  Users, 
  Store, 
  BookOpen, 
  Calendar, 
  PlusCircle, 
  Search, 
  Filter, 
  Heart, 
  Phone, 
  Mail, 
  MapPin, 
  Briefcase, 
  GraduationCap, 
  ShieldCheck, 
  Award, 
  Share2, 
  ExternalLink, 
  CheckCircle, 
  Sparkles, 
  Building2, 
  FileText,
  ChevronRight,
  Menu,
  X,
  Eye,
  MessageSquare
} from 'lucide-react';

// --- MOCK DATA ---
const INITIAL_PROFILES = [
  {
    id: 1,
    name: "Vikram Rathore",
    age: 27,
    gender: "Male",
    gotra: "Chauhan",
    city: "Indore",
    state: "Madhya Pradesh",
    education: "B.Tech in Computer Science",
    profession: "Software Engineer at MNC",
    income: "₹14-16 LPA",
    height: "5' 10\"",
    familyDetails: "Father: Merchant (Business), Mother: Homemaker, 1 Sister (Married)",
    photo: "https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=400&q=80",
    verified: true,
    contact: "+91 98765 43210",
    about: "Looking for an educated, understanding partner with traditional yet modern values."
  },
  {
    id: 2,
    name: "Pooja Rathore",
    age: 25,
    gender: "Female",
    gotra: "Parihar",
    city: "Ujjain",
    state: "Madhya Pradesh",
    education: "M.Com, B.Ed",
    profession: "High School Teacher",
    income: "₹4.5 - 6 LPA",
    height: "5' 4\"",
    familyDetails: "Father: Govt Officer, Mother: Teacher, 1 Brother (Studying)",
    photo: "https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=400&q=80",
    verified: true,
    contact: "+91 98765 12345",
    about: "Passionate about teaching and cultural roots. Enjoys painting, music, and family gatherings."
  },
  {
    id: 3,
    name: "Rahul Rathore",
    age: 29,
    gender: "Male",
    gotra: "Solanki",
    city: "Bhopal",
    state: "Madhya Pradesh",
    education: "MBA in Marketing",
    profession: "Business Owner (Textiles & Garments)",
    income: "₹18-22 LPA",
    height: "5' 9\"",
    familyDetails: "Father: Business Head, Mother: Homemaker, 2 Brothers",
    photo: "https://images.unsplash.com/photo-1500648767791-00dcc994a43e?auto=format&fit=crop&w=400&q=80",
    verified: true,
    contact: "+91 98260 99887",
    about: "Managing family retail store network in Bhopal. Looking for a supportive lifecycle companion."
  },
  {
    id: 4,
    name: "Neha Rathore",
    age: 24,
    gender: "Female",
    gotra: "Rathod",
    city: "Jaipur",
    state: "Rajasthan",
    education: "B.Pharm / M.Pharm",
    profession: "Clinical Researcher",
    income: "₹7-9 LPA",
    height: "5' 5\"",
    familyDetails: "Father: Retired Bank Mgr, Mother: Homemaker, 1 Sister",
    photo: "https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=400&q=80",
    verified: true,
    contact: "+91 94140 33221",
    about: "Simplicity and sincerity are my core values. Family-oriented and hardworking."
  }
];

const INITIAL_ADS = [
  {
    id: 1,
    title: "Rathore Saree & Textile Emporium",
    owner: "Rameshwar Rathore",
    category: "Clothing & Retail",
    city: "Indore",
    address: "142, Rajwada Main Market, Indore",
    phone: "+91 98261 11223",
    tagline: "Exclusive Silk Sarees, Bridal Lehengas & Designer Suits for all occasions.",
    offer: "10% Discount for Rathore Samaj Members!",
    rating: "4.9 ★",
    isFeatured: true,
    banner: "https://images.unsplash.com/photo-1610030469983-98e550d6193c?auto=format&fit=crop&w=600&q=80"
  },
  {
    id: 2,
    title: "Shree Rathore Hardware & Electronics",
    owner: "Suresh Rathore",
    category: "Hardware & Home Imprv.",
    city: "Ujjain",
    address: "45, Freeganj Tower Road, Ujjain",
    phone: "+91 94250 55443",
    tagline: "Wholesale & Retail in Quality Electricals, Sanitaryware & Paints.",
    offer: "Free Delivery within 15 km",
    rating: "4.8 ★",
    isFeatured: false,
    banner: "https://images.unsplash.com/photo-1581092160607-ee22621dd758?auto=format&fit=crop&w=600&q=80"
  },
  {
    id: 3,
    title: "Rathore Caterers & Event Decorators",
    owner: "Kailash Rathore",
    category: "Event Management",
    city: "Bhopal",
    address: "88, MP Nagar Zone 2, Bhopal",
    phone: "+91 99933 77112",
    tagline: "Authentic Pure Veg Rajasthani & Malwi Cuisine for Weddings & Samiti Sammelans.",
    offer: "Special Package for Samaj Sammelan Bookings",
    rating: "5.0 ★",
    isFeatured: true,
    banner: "https://images.unsplash.com/photo-1555244162-803834f70033?auto=format&fit=crop&w=600&q=80"
  }
];

const EVENTS = [
  {
    id: 1,
    title: "Var-Vadhu Parichay Sammelan 2026",
    date: "15th November 2026",
    time: "10:00 AM - 5:00 PM",
    venue: "Abhay Prashal Auditorium, Race Course Road, Indore",
    organizedBy: "Akhil Bharatiya Rathore Samaj Samiti",
    description: "Annual grand matrimonial meet up for eligible Rathore boys and girls. Registration required before 10th Nov.",
    badge: "Grand Event"
  },
  {
    id: 2,
    title: "Rathore Samaj Youth & Business Expo",
    date: "5th December 2026",
    time: "11:00 AM Onwards",
    venue: "Community Hall, Freeganj, Ujjain",
    organizedBy: "Rathore Vyapar Mandal",
    description: "Exhibition for community entrepreneurs to network, display products, and expand local trade connections.",
    badge: "Networking"
  }
];

export default function App() {
  const [activeTab, setActiveTab] = useState('matrimony');
  const [profiles, setProfiles] = useState(INITIAL_PROFILES);
  const [ads, setAds] = useState(INITIAL_ADS);
  const [favorites, setFavorites] = useState([]);
  
  // Filter States
  const [searchTerm, setSearchTerm] = useState('');
  const [genderFilter, setGenderFilter] = useState('all');
  const [gotraFilter, setGotraFilter] = useState('');
  const [cityFilter, setCityFilter] = useState('');

  // Selected Item Modal
  const [selectedProfile, setSelectedProfile] = useState(null);
  const [selectedAd, setSelectedAd] = useState(null);

  // Mobile Menu State
  const [isMobileMenuOpen, setIsMobileMenuOpen] = useState(false);

  // Submission Form Modals
  const [showAddProfileModal, setShowAddProfileModal] = useState(false);
  const [showAddAdModal, setShowAddAdModal] = useState(false);

  // New Profile Form Input
  const [newProfile, setNewProfile] = useState({
    name: '', age: '', gender: 'Male', gotra: '', city: 'Indore',
    education: '', profession: '', income: '', height: '', familyDetails: '', about: '', contact: ''
  });

  // New Business Ad Form Input
  const [newAd, setNewAd] = useState({
    title: '', owner: '', category: 'Retail', city: 'Indore', address: '', phone: '', tagline: '', offer: ''
  });

  // Toggle Favorite Profile
  const toggleFavorite = (id) => {
    setFavorites(prev => 
      prev.includes(id) ? prev.filter(item => item !== id) : [...prev, id]
    );
  };

  // Filtered Profiles Logic
  const filteredProfiles = useMemo(() => {
    return profiles.filter(p => {
      const matchSearch = p.name.toLowerCase().includes(searchTerm.toLowerCase()) || 
                          p.profession.toLowerCase().includes(searchTerm.toLowerCase()) ||
                          p.education.toLowerCase().includes(searchTerm.toLowerCase());
      const matchGender = genderFilter === 'all' || p.gender === genderFilter;
      const matchGotra = !gotraFilter || p.gotra.toLowerCase().includes(gotraFilter.toLowerCase());
      const matchCity = !cityFilter || p.city.toLowerCase().includes(cityFilter.toLowerCase());
      return matchSearch && matchGender && matchGotra && matchCity;
    });
  }, [profiles, searchTerm, genderFilter, gotraFilter, cityFilter]);

  // Handle New Matrimony Profile Submit
  const handleProfileSubmit = (e) => {
    e.preventDefault();
    const createdProfile = {
      ...newProfile,
      id: Date.now(),
      verified: true,
      photo: newProfile.gender === 'Female' 
        ? "https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=400&q=80" 
        : "https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=400&q=80"
    };
    setProfiles([createdProfile, ...profiles]);
    setShowAddProfileModal(false);
    setNewProfile({ name: '', age: '', gender: 'Male', gotra: '', city: 'Indore', education: '', profession: '', income: '', height: '', familyDetails: '', about: '', contact: '' });
  };

  // Handle New Business Ad Submit
  const handleAdSubmit = (e) => {
    e.preventDefault();
    const createdAd = {
      ...newAd,
      id: Date.now(),
      rating: "5.0 ★",
      isFeatured: true,
      banner: "https://images.unsplash.com/photo-1441986300917-64674bd600d8?auto=format&fit=crop&w=600&q=80"
    };
    setAds([createdAd, ...ads]);
    setShowAddAdModal(false);
    setNewAd({ title: '', owner: '', category: 'Retail', city: 'Indore', address: '', phone: '', tagline: '', offer: '' });
  };

  return (
    <div className="min-h-screen bg-amber-50/40 text-slate-800 font-sans flex flex-col">
      {/* APP BAR HEADER */}
      <header className="sticky top-0 z-40 bg-gradient-to-r from-red-900 via-rose-900 to-amber-900 text-white shadow-xl border-b-2 border-amber-500/40">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="flex items-center justify-between h-20">
            {/* Branding Logo */}
            <div className="flex items-center space-x-3 cursor-pointer" onClick={() => setActiveTab('matrimony')}>
              <div className="w-12 h-12 rounded-full bg-gradient-to-tr from-amber-400 to-amber-200 text-red-950 font-bold flex items-center justify-center text-xl shadow-lg border-2 border-amber-300">
                RR
              </div>
              <div>
                <h1 className="text-2xl font-extrabold tracking-wide text-amber-100 flex items-center gap-1.5 font-serif">
                  Rathore Rishtey
                  <ShieldCheck className="w-5 h-5 text-amber-300 fill-amber-300/20 inline" />
                </h1>
                <p className="text-xs text-amber-200/80 font-medium">Digital Matrimony & Business Directory</p>
              </div>
            </div>

            {/* Desktop Navigation */}
            <nav className="hidden md:flex space-x-1 lg:space-x-2">
              <button
                onClick={() => setActiveTab('matrimony')}
                className={`flex items-center gap-2 px-4 py-2.5 rounded-lg text-sm font-semibold transition-all ${
                  activeTab === 'matrimony'
                    ? 'bg-amber-500 text-red-950 shadow-md font-bold'
                    : 'text-amber-100 hover:bg-white/10'
                }`}
              >
                <Users className="w-4 h-4" />
                Matrimony Bios
              </button>

              <button
                onClick={() => setActiveTab('directory')}
                className={`flex items-center gap-2 px-4 py-2.5 rounded-lg text-sm font-semibold transition-all ${
                  activeTab === 'directory'
                    ? 'bg-amber-500 text-red-950 shadow-md font-bold'
                    : 'text-amber-100 hover:bg-white/10'
                }`}
              >
                <Store className="w-4 h-4" />
                Business Ads
              </button>

              <button
                onClick={() => setActiveTab('booklet')}
                className={`flex items-center gap-2 px-4 py-2.5 rounded-lg text-sm font-semibold transition-all ${
                  activeTab === 'booklet'
                    ? 'bg-amber-500 text-red-950 shadow-md font-bold'
                    : 'text-amber-100 hover:bg-white/10'
                }`}
              >
                <BookOpen className="w-4 h-4" />
                Digital E-Book
              </button>

              <button
                onClick={() => setActiveTab('events')}
                className={`flex items-center gap-2 px-4 py-2.5 rounded-lg text-sm font-semibold transition-all ${
                  activeTab === 'events'
                    ? 'bg-amber-500 text-red-950 shadow-md font-bold'
                    : 'text-amber-100 hover:bg-white/10'
                }`}
              >
                <Calendar className="w-4 h-4" />
                Samaj Events
              </button>
            </nav>

            {/* Quick Action CTA Button */}
            <div className="hidden lg:flex items-center space-x-3">
              <button
                onClick={() => setShowAddProfileModal(true)}
                className="bg-gradient-to-r from-amber-400 to-amber-500 hover:from-amber-300 hover:to-amber-400 text-red-950 font-bold px-4 py-2 rounded-lg text-xs shadow-md transition-all flex items-center gap-1.5"
              >
                <PlusCircle className="w-4 h-4" />
                Add Bio Form
              </button>
              <button
                onClick={() => setShowAddAdModal(true)}
                className="bg-red-800 hover:bg-red-700 text-amber-200 border border-amber-400/40 font-semibold px-4 py-2 rounded-lg text-xs transition-all flex items-center gap-1.5"
              >
                <Store className="w-4 h-4" />
                Advertise Shop
              </button>
            </div>

            {/* Mobile Menu Toggle Button */}
            <div className="md:hidden flex items-center">
              <button
                onClick={() => setIsMobileMenuOpen(!isMobileMenuOpen)}
                className="p-2 rounded-md text-amber-200 hover:text-white hover:bg-white/10"
              >
                {isMobileMenuOpen ? <X className="w-6 h-6" /> : <Menu className="w-6 h-6" />}
              </button>
            </div>
          </div>
        </div>

        {/* Mobile Navigation Dropdown */}
        {isMobileMenuOpen && (
          <div className="md:hidden bg-red-950 border-t border-amber-500/30 px-4 pt-2 pb-4 space-y-2">
            <button
              onClick={() => { setActiveTab('matrimony'); setIsMobileMenuOpen(false); }}
              className={`w-full text-left px-3 py-2 rounded-md font-medium text-sm flex items-center gap-2 ${
                activeTab === 'matrimony' ? 'bg-amber-500 text-red-950 font-bold' : 'text-amber-100'
              }`}
            >
              <Users className="w-4 h-4" /> Matrimony Bios
            </button>
            <button
              onClick={() => { setActiveTab('directory'); setIsMobileMenuOpen(false); }}
              className={`w-full text-left px-3 py-2 rounded-md font-medium text-sm flex items-center gap-2 ${
                activeTab === 'directory' ? 'bg-amber-500 text-red-950 font-bold' : 'text-amber-100'
              }`}
            >
              <Store className="w-4 h-4" /> Business Directory & Ads
            </button>
            <button
              onClick={() => { setActiveTab('booklet'); setIsMobileMenuOpen(false); }}
              className={`w-full text-left px-3 py-2 rounded-md font-medium text-sm flex items-center gap-2 ${
                activeTab === 'booklet' ? 'bg-amber-500 text-red-950 font-bold' : 'text-amber-100'
              }`}
            >
              <BookOpen className="w-4 h-4" /> Digital E-Book Directory
            </button>
            <button
              onClick={() => { setActiveTab('events'); setIsMobileMenuOpen(false); }}
              className={`w-full text-left px-3 py-2 rounded-md font-medium text-sm flex items-center gap-2 ${
                activeTab === 'events' ? 'bg-amber-500 text-red-950 font-bold' : 'text-amber-100'
              }`}
            >
              <Calendar className="w-4 h-4" /> Samaj Events & News
            </button>
            <div className="pt-2 flex flex-col space-y-2 border-t border-amber-800">
              <button
                onClick={() => { setShowAddProfileModal(true); setIsMobileMenuOpen(false); }}
                className="w-full bg-amber-500 text-red-950 font-bold py-2 rounded-md text-xs text-center"
              >
                + Register Matrimony Profile
              </button>
              <button
                onClick={() => { setShowAddAdModal(true); setIsMobileMenuOpen(false); }}
                className="w-full bg-red-800 text-amber-200 border border-amber-400/40 font-bold py-2 rounded-md text-xs text-center"
              >
                + Submit Business Advertisement
              </button>
            </div>
          </div>
        )}
      </header>

      {/* HERO BANNER ANNOUNCEMENT */}
      <div className="bg-gradient-to-r from-amber-100 via-amber-50 to-orange-100 border-b border-amber-200 px-4 py-3 text-center text-sm text-red-950 font-medium">
        <span className="bg-red-800 text-amber-100 text-xs font-bold px-2 py-0.5 rounded-full mr-2">ANNUAL DIRECTORY 2026</span>
        <span>Welcome Rathore Samaj Members! Instead of printed books, access 100% verified rishta profiles & local business ads instantly.</span>
      </div>

      {/* MAIN CONTAINER CONTENT */}
      <main className="flex-1 max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-6">

        {/* TAB 1: MATRIMONY PROFILES */}
        {activeTab === 'matrimony' && (
          <div className="space-y-6">
            {/* SEARCH & FILTERS SECTION */}
            <div className="bg-white rounded-2xl shadow-md border border-amber-200 p-5">
              <div className="flex flex-col lg:flex-row gap-4 justify-between items-center mb-4">
                <div className="relative w-full lg:w-96">
                  <Search className="absolute left-3 top-3 w-5 h-5 text-amber-700/60" />
                  <input
                    type="text"
                    placeholder="Search name, qualification, profession..."
                    value={searchTerm}
                    onChange={(e) => setSearchTerm(e.target.value)}
                    className="w-full pl-10 pr-4 py-2.5 rounded-xl border border-amber-300 focus:outline-none focus:ring-2 focus:ring-amber-500 text-sm bg-amber-50/20"
                  />
                </div>

                <div className="flex flex-wrap gap-2 w-full lg:w-auto items-center">
                  {/* Gender Filter */}
                  <div className="flex bg-amber-100/70 p-1 rounded-xl border border-amber-200">
                    <button
                      onClick={() => setGenderFilter('all')}
                      className={`px-3 py-1.5 rounded-lg text-xs font-semibold ${
                        genderFilter === 'all' ? 'bg-red-900 text-white shadow' : 'text-red-900'
                      }`}
                    >
                      All
                    </button>
                    <button
                      onClick={() => setGenderFilter('Male')}
                      className={`px-3 py-1.5 rounded-lg text-xs font-semibold ${
                        genderFilter === 'Male' ? 'bg-red-900 text-white shadow' : 'text-red-900'
                      }`}
                    >
                      Grooms (Groom)
                    </button>
                    <button
                      onClick={() => setGenderFilter('Female')}
                      className={`px-3 py-1.5 rounded-lg text-xs font-semibold ${
                        genderFilter === 'Female' ? 'bg-red-900 text-white shadow' : 'text-red-900'
                      }`}
                    >
                      Brides (Bride)
                    </button>
                  </div>

                  {/* Gotra Selector */}
                  <input
                    type="text"
                    placeholder="Filter Gotra..."
                    value={gotraFilter}
                    onChange={(e) => setGotraFilter(e.target.value)}
                    className="px-3 py-2 rounded-xl border border-amber-300 text-xs w-32 focus:outline-none focus:ring-2 focus:ring-amber-500"
                  />

                  {/* City Selector */}
                  <input
                    type="text"
                    placeholder="Filter City..."
                    value={cityFilter}
                    onChange={(e) => setCityFilter(e.target.value)}
                    className="px-3 py-2 rounded-xl border border-amber-300 text-xs w-32 focus:outline-none focus:ring-2 focus:ring-amber-500"
                  />
                </div>
              </div>

              <div className="flex justify-between items-center text-xs text-slate-500 pt-2 border-t border-amber-100">
                <span>Showing <strong>{filteredProfiles.length}</strong> Rathore Samaj Biodatas</span>
                <span className="text-red-800 font-semibold cursor-pointer hover:underline" onClick={() => setShowAddProfileModal(true)}>
                  + Click to register your family's profile
                </span>
              </div>
            </div>

            {/* MATRIMONY CARDS GRID */}
            <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-6">
              {filteredProfiles.map((p) => (
                <div 
                  key={p.id}
                  className="bg-white rounded-2xl shadow-md hover:shadow-xl transition-all duration-300 border border-amber-200/70 overflow-hidden flex flex-col sm:flex-row"
                >
                  {/* Photo Container */}
                  <div className="sm:w-2/5 relative h-64 sm:h-auto bg-amber-100">
                    <img 
                      src={p.photo} 
                      alt={p.name}
                      className="w-full h-full object-cover"
                    />
                    <div className="absolute top-3 left-3 bg-red-900/90 text-amber-200 text-xs font-semibold px-2.5 py-1 rounded-full shadow backdrop-blur-sm">
                      Gotra: {p.gotra}
                    </div>
                    <button
                      onClick={() => toggleFavorite(p.id)}
                      className="absolute top-3 right-3 w-8 h-8 rounded-full bg-white/80 backdrop-blur-sm flex items-center justify-center text-red-600 hover:bg-white transition-all shadow"
                    >
                      <Heart className={`w-4 h-4 ${favorites.includes(p.id) ? 'fill-red-600' : ''}`} />
                    </button>
                  </div>

                  {/* Profile Details */}
                  <div className="p-5 sm:w-3/5 flex flex-col justify-between">
                    <div>
                      <div className="flex justify-between items-start">
                        <div>
                          <h3 className="text-xl font-bold text-slate-900 font-serif flex items-center gap-1">
                            {p.name}
                            {p.verified && <CheckCircle className="w-4 h-4 text-emerald-600 inline" />}
                          </h3>
                          <p className="text-xs text-amber-800 font-semibold">{p.age} Yrs • {p.height}</p>
                        </div>
                        <span className="text-xs font-bold bg-amber-100 text-amber-900 px-2.5 py-1 rounded-md">
                          {p.city}
                        </span>
                      </div>

                      <div className="mt-4 space-y-2 text-xs text-slate-600">
                        <div className="flex items-center gap-2">
                          <GraduationCap className="w-4 h-4 text-amber-700 shrink-0" />
                          <span className="truncate">{p.education}</span>
                        </div>
                        <div className="flex items-center gap-2">
                          <Briefcase className="w-4 h-4 text-amber-700 shrink-0" />
                          <span className="truncate">{p.profession}</span>
                        </div>
                        <div className="flex items-center gap-2">
                          <MapPin className="w-4 h-4 text-amber-700 shrink-0" />
                          <span>{p.city}, {p.state}</span>
                        </div>
                      </div>

                      <p className="mt-3 text-xs text-slate-500 line-clamp-2 italic bg-amber-50/50 p-2 rounded-lg border border-amber-100">
                        "{p.about}"
                      </p>
                    </div>

                    <div className="mt-4 pt-3 border-t border-slate-100 flex items-center gap-2">
                      <button 
                        onClick={() => setSelectedProfile(p)}
                        className="flex-1 bg-gradient-to-r from-red-900 to-rose-900 hover:from-red-800 hover:to-rose-800 text-amber-100 text-xs font-bold py-2.5 px-3 rounded-xl shadow transition-all flex items-center justify-center gap-1"
                      >
                        <Eye className="w-3.5 h-3.5" /> View Full Biodata
                      </button>
                      <a 
                        href={`tel:${p.contact}`}
                        className="bg-emerald-50 text-emerald-700 hover:bg-emerald-100 p-2.5 rounded-xl border border-emerald-200 transition-all"
                        title="Call Contact"
                      >
                        <Phone className="w-4 h-4" />
                      </a>
                    </div>
                  </div>
                </div>
              ))}
            </div>
          </div>
        )}

        {/* TAB 2: BUSINESS DIRECTORY & ADS */}
        {activeTab === 'directory' && (
          <div className="space-y-6">
            {/* DIRECTORY HEADER & ADD AD BANNER */}
            <div className="bg-gradient-to-r from-red-950 via-rose-950 to-amber-950 rounded-2xl p-6 text-white shadow-xl flex flex-col md:flex-row justify-between items-center gap-4 border border-amber-500/30">
              <div>
                <span className="bg-amber-400 text-red-950 text-xs font-extrabold px-3 py-1 rounded-full uppercase tracking-wider">
                  Rathore Samaj Business Network
                </span>
                <h2 className="text-2xl font-bold font-serif text-amber-100 mt-2">Promote Your Shop & Services</h2>
                <p className="text-xs text-amber-200/80 mt-1 max-w-xl">
                  Reach thousands of Rathore Samaj families across cities. Replace traditional booklet ads with interactive digital business listings.
                </p>
              </div>
              <button
                onClick={() => setShowAddAdModal(true)}
                className="bg-amber-400 hover:bg-amber-300 text-red-950 font-extrabold px-5 py-3 rounded-xl shadow-lg transition-all text-sm shrink-0 flex items-center gap-2"
              >
                <PlusCircle className="w-5 h-5" />
                Post Shop Advertisement
              </button>
            </div>

            {/* ADS GRID */}
            <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
              {ads.map((ad) => (
                <div 
                  key={ad.id}
                  className="bg-white rounded-2xl shadow-md hover:shadow-xl transition-all duration-300 border border-amber-200 overflow-hidden flex flex-col justify-between"
                >
                  <div>
                    {/* Business Banner Image */}
                    <div className="relative h-44 bg-slate-100">
                      <img 
                        src={ad.banner} 
                        alt={ad.title}
                        className="w-full h-full object-cover"
                      />
                      <div className="absolute top-3 left-3 bg-red-950 text-amber-300 text-xs font-bold px-2.5 py-1 rounded-md shadow">
                        {ad.category}
                      </div>
                      {ad.isFeatured && (
                        <div className="absolute top-3 right-3 bg-amber-400 text-red-950 text-xs font-extrabold px-2 py-0.5 rounded shadow flex items-center gap-1">
                          <Sparkles className="w-3 h-3" /> Featured Ad
                        </div>
                      )}
                    </div>

                    {/* Ad Info */}
                    <div className="p-5">
                      <div className="flex justify-between items-start mb-2">
                        <h3 className="font-bold text-lg text-slate-900 font-serif leading-tight">
                          {ad.title}
                        </h3>
                      </div>
                      <p className="text-xs font-semibold text-amber-800 mb-2">Owner: {ad.owner}</p>

                      <p className="text-xs text-slate-600 line-clamp-2 mb-3">
                        {ad.tagline}
                      </p>

                      {ad.offer && (
                        <div className="bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs p-2 rounded-lg font-semibold flex items-center gap-1.5 mb-3">
                          <Award className="w-4 h-4 text-emerald-600 shrink-0" />
                          <span>{ad.offer}</span>
                        </div>
                      )}

                      <div className="space-y-1.5 text-xs text-slate-500">
                        <div className="flex items-center gap-1.5">
                          <MapPin className="w-3.5 h-3.5 text-amber-700 shrink-0" />
                          <span className="truncate">{ad.address}</span>
                        </div>
                        <div className="flex items-center gap-1.5">
                          <Phone className="w-3.5 h-3.5 text-amber-700 shrink-0" />
                          <span>{ad.phone}</span>
                        </div>
                      </div>
                    </div>
                  </div>

                  {/* Actions */}
                  <div className="p-5 pt-0">
                    <button
                      onClick={() => setSelectedAd(ad)}
                      className="w-full bg-slate-900 hover:bg-slate-800 text-amber-200 font-bold py-2 rounded-xl text-xs transition-all flex items-center justify-center gap-1"
                    >
                      View Shop Details & Offer
                    </button>
                  </div>
                </div>
              ))}
            </div>
          </div>
        )}

        {/* TAB 3: DIGITAL E-BOOKLET VIEWER */}
        {activeTab === 'booklet' && (
          <div className="bg-white rounded-2xl shadow-xl border border-amber-200 p-6 md:p-8 space-y-6">
            <div className="text-center max-w-2xl mx-auto">
              <span className="bg-amber-100 text-amber-900 text-xs font-bold px-3 py-1 rounded-full uppercase">
                Interactive Directory
              </span>
              <h2 className="text-3xl font-serif font-bold text-red-950 mt-2">Annual Rathore Samaj E-Booklet</h2>
              <p className="text-xs text-slate-600 mt-2">
                Flip through the digitized pages of our community directory, just like the traditional printed book handed out by samiti adhyaksh.
              </p>
            </div>

            {/* E-BOOK SIMULATOR CONTAINER */}
            <div className="bg-amber-900/10 border-2 border-dashed border-amber-400/50 rounded-2xl p-6 md:p-10 flex flex-col items-center justify-center text-center space-y-4">
              <BookOpen className="w-16 h-16 text-red-900 animate-bounce" />
              <div className="space-y-1">
                <h4 className="font-serif font-bold text-lg text-slate-900">Rathore Samaj Patrika 2026 (Digital Edition)</h4>
                <p className="text-xs text-slate-500">Contains 450+ Matrimonial Profiles & 120 Local Business Sponsor Ads</p>
              </div>

              <div className="flex flex-wrap gap-3 justify-center pt-2">
                <button 
                  onClick={() => alert("Downloading full PDF booklet (45 MB)...")}
                  className="bg-red-900 hover:bg-red-800 text-amber-100 text-xs font-bold px-5 py-2.5 rounded-xl shadow transition-all flex items-center gap-2"
                >
                  <FileText className="w-4 h-4" /> Download Printable PDF
                </button>
                <button 
                  onClick={() => setActiveTab('matrimony')}
                  className="bg-amber-400 hover:bg-amber-300 text-red-950 text-xs font-bold px-5 py-2.5 rounded-xl shadow transition-all flex items-center gap-2"
                >
                  <Search className="w-4 h-4" /> Search Digitized Records
                </button>
              </div>
            </div>
          </div>
        )}

        {/* TAB 4: SAMAJ EVENTS & NEWS */}
        {activeTab === 'events' && (
          <div className="space-y-6">
            <div className="text-center max-w-2xl mx-auto py-2">
              <h2 className="text-3xl font-serif font-bold text-red-950">Samaj Sammelans & News</h2>
              <p className="text-xs text-slate-600 mt-1">Stay updated with upcoming matrimonial meets, adhyaksh notices, and community gatherings.</p>
            </div>

            <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
              {EVENTS.map((evt) => (
                <div key={evt.id} className="bg-white rounded-2xl shadow-md border border-amber-200 p-6 flex flex-col justify-between">
                  <div>
                    <div className="flex justify-between items-start mb-3">
                      <span className="bg-red-100 text-red-900 text-xs font-bold px-3 py-1 rounded-full">
                        {evt.badge}
                      </span>
                      <span className="text-xs font-semibold text-amber-800 flex items-center gap-1">
                        <Calendar className="w-3.5 h-3.5" /> {evt.date}
                      </span>
                    </div>

                    <h3 className="text-xl font-bold font-serif text-slate-900 mb-2">{evt.title}</h3>
                    <p className="text-xs text-slate-600 mb-4">{evt.description}</p>

                    <div className="space-y-2 text-xs text-slate-500 border-t border-amber-100 pt-3">
                      <div className="flex items-start gap-2">
                        <MapPin className="w-4 h-4 text-amber-700 shrink-0 mt-0.5" />
                        <span><strong>Venue:</strong> {evt.venue}</span>
                      </div>
                      <div className="flex items-center gap-2">
                        <Building2 className="w-4 h-4 text-amber-700 shrink-0" />
                        <span><strong>Organizers:</strong> {evt.organizedBy}</span>
                      </div>
                    </div>
                  </div>

                  <button 
                    onClick={() => alert(`Registered interest for: ${evt.title}`)}
                    className="mt-6 w-full bg-red-900 hover:bg-red-800 text-amber-100 font-bold py-2.5 rounded-xl text-xs shadow transition-all"
                  >
                    Confirm Attendance / Register
                  </button>
                </div>
              ))}
            </div>
          </div>
        )}
      </main>

      {/* FOOTER */}
      <footer className="bg-red-950 text-amber-200/80 border-t border-amber-500/30 py-8 px-4 sm:px-6 lg:px-8 mt-12">
        <div className="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-4 text-xs">
          <div>
            <p className="font-bold text-amber-100 text-sm font-serif">Rathore Rishtey & Directory Portal</p>
            <p className="mt-1">Dedicated digital platform for Rathore Samaj families and local shop owners.</p>
          </div>
          <div className="flex space-x-4">
            <button onClick={() => setActiveTab('matrimony')} className="hover:text-amber-300">Matrimony</button>
            <button onClick={() => setActiveTab('directory')} className="hover:text-amber-300">Business Ads</button>
            <button onClick={() => setActiveTab('booklet')} className="hover:text-amber-300">E-Booklet</button>
            <button onClick={() => setActiveTab('events')} className="hover:text-amber-300">Samaj Events</button>
          </div>
        </div>
      </footer>

      {/* MODAL: VIEW DETAILED MATRIMONY PROFILE */}
      {selectedProfile && (
        <div className="fixed inset-0 z-50 bg-black/60 backdrop-blur-sm flex items-center justify-center p-4 overflow-y-auto">
          <div className="bg-white rounded-3xl max-w-xl w-full p-6 shadow-2xl border border-amber-300 relative animate-in fade-in zoom-in duration-200">
            <button 
              onClick={() => setSelectedProfile(null)}
              className="absolute top-4 right-4 text-slate-400 hover:text-slate-600 p-1 rounded-full"
            >
              <X className="w-6 h-6" />
            </button>

            <div className="flex flex-col sm:flex-row gap-5 items-center sm:items-start">
              <img 
                src={selectedProfile.photo} 
                alt={selectedProfile.name}
                className="w-32 h-32 rounded-2xl object-cover border-2 border-amber-400 shadow-md shrink-0" 
              />
              <div>
                <span className="bg-amber-100 text-amber-900 text-xs font-bold px-2.5 py-0.5 rounded-full">
                  Gotra: {selectedProfile.gotra}
                </span>
                <h2 className="text-2xl font-bold font-serif text-slate-900 mt-1 flex items-center gap-1.5">
                  {selectedProfile.name}
                  <CheckCircle className="w-5 h-5 text-emerald-600 inline" />
                </h2>
                <p className="text-xs text-slate-500 font-semibold">{selectedProfile.age} Yrs • {selectedProfile.height} • {selectedProfile.city}</p>
                <p className="text-xs text-emerald-700 font-bold mt-1">Income: {selectedProfile.income}</p>
              </div>
            </div>

            <div className="mt-6 space-y-4 border-t border-amber-100 pt-4 text-xs">
              <div>
                <h4 className="font-bold text-slate-800 uppercase tracking-wider text-[11px]">Educational & Professional Details</h4>
                <div className="grid grid-cols-2 gap-2 mt-2 bg-amber-50/50 p-3 rounded-xl border border-amber-100">
                  <div><span className="text-slate-500">Education:</span> <p className="font-semibold">{selectedProfile.education}</p></div>
                  <div><span className="text-slate-500">Profession:</span> <p className="font-semibold">{selectedProfile.profession}</p></div>
                </div>
              </div>

              <div>
                <h4 className="font-bold text-slate-800 uppercase tracking-wider text-[11px]">Family Background</h4>
                <p className="mt-1 text-slate-600 bg-amber-50/50 p-3 rounded-xl border border-amber-100">
                  {selectedProfile.familyDetails}
                </p>
              </div>

              <div>
                <h4 className="font-bold text-slate-800 uppercase tracking-wider text-[11px]">About Candidate</h4>
                <p className="mt-1 text-slate-600 bg-amber-50/50 p-3 rounded-xl border border-amber-100">
                  {selectedProfile.about}
                </p>
              </div>

              <div>
                <h4 className="font-bold text-slate-800 uppercase tracking-wider text-[11px]">Contact & Family Reachout</h4>
                <div className="mt-2 bg-emerald-50 border border-emerald-200 p-3 rounded-xl flex justify-between items-center">
                  <div>
                    <p className="text-emerald-900 font-bold">{selectedProfile.contact}</p>
                    <p className="text-[10px] text-emerald-700">Verified Rathore Samaj Family Member</p>
                  </div>
                  <a 
                    href={`tel:${selectedProfile.contact}`}
                    className="bg-emerald-600 text-white font-bold px-4 py-2 rounded-lg text-xs hover:bg-emerald-700 transition-all flex items-center gap-1.5"
                  >
                    <Phone className="w-3.5 h-3.5" /> Call Family
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      )}

      {/* MODAL: VIEW DETAILED BUSINESS AD */}
      {selectedAd && (
        <div className="fixed inset-0 z-50 bg-black/60 backdrop-blur-sm flex items-center justify-center p-4 overflow-y-auto">
          <div className="bg-white rounded-3xl max-w-lg w-full p-6 shadow-2xl border border-amber-300 relative animate-in fade-in zoom-in duration-200">
            <button 
              onClick={() => setSelectedAd(null)}
              className="absolute top-4 right-4 text-slate-400 hover:text-slate-600 p-1 rounded-full"
            >
              <X className="w-6 h-6" />
            </button>

            <img src={selectedAd.banner} alt={selectedAd.title} className="w-full h-40 object-cover rounded-2xl mb-4" />

            <span className="bg-red-900 text-amber-200 text-xs font-bold px-2.5 py-1 rounded-md">
              {selectedAd.category}
            </span>
            <h2 className="text-2xl font-bold font-serif text-slate-900 mt-2">{selectedAd.title}</h2>
            <p className="text-xs text-amber-800 font-semibold">Proprietor: {selectedAd.owner}</p>

            <div className="mt-4 space-y-3 text-xs">
              <div className="bg-amber-50 p-3 rounded-xl border border-amber-200 text-slate-700">
                <p className="font-medium">{selectedAd.tagline}</p>
              </div>

              {selectedAd.offer && (
                <div className="bg-emerald-50 border border-emerald-300 p-3 rounded-xl text-emerald-900 font-bold flex items-center gap-2">
                  <Award className="w-5 h-5 text-emerald-600 shrink-0" />
                  <div>
                    <p className="text-[10px] uppercase tracking-wide text-emerald-700 font-bold">Samaj Exclusive Discount</p>
                    <p>{selectedAd.offer}</p>
                  </div>
                </div>
              )}

              <div className="space-y-2 pt-2 text-slate-600">
                <p><strong>Address:</strong> {selectedAd.address}</p>
                <p><strong>City:</strong> {selectedAd.city}</p>
                <p><strong>Phone:</strong> {selectedAd.phone}</p>
              </div>

              <div className="pt-3">
                <a 
                  href={`tel:${selectedAd.phone}`}
                  className="w-full bg-slate-900 hover:bg-slate-800 text-amber-200 font-bold py-3 rounded-xl text-xs flex items-center justify-center gap-2 transition-all shadow"
                >
                  <Phone className="w-4 h-4" /> Call Shop Owner Directly
                </a>
              </div>
            </div>
          </div>
        </div>
      )}

      {/* MODAL: ADD MATRIMONY PROFILE FORM */}
      {showAddProfileModal && (
        <div className="fixed inset-0 z-50 bg-black/60 backdrop-blur-sm flex items-center justify-center p-4 overflow-y-auto">
          <div className="bg-white rounded-3xl max-w-xl w-full p-6 shadow-2xl border border-amber-300 relative my-8">
            <button 
              onClick={() => setShowAddProfileModal(false)}
              className="absolute top-4 right-4 text-slate-400 hover:text-slate-600 p-1 rounded-full"
            >
              <X className="w-6 h-6" />
            </button>

            <h2 className="text-2xl font-serif font-bold text-red-950 mb-1">Register Biodata Form</h2>
            <p className="text-xs text-slate-500 mb-4">Fill out your family details for the Rathore Samaj matrimonial directory.</p>

            <form onSubmit={handleProfileSubmit} className="space-y-3 text-xs">
              <div className="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label className="font-bold text-slate-700">Full Name *</label>
                  <input required type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="e.g. Rahul Rathore" value={newProfile.name} onChange={e => setNewProfile({...newProfile, name: e.target.value})} />
                </div>
                <div>
                  <label className="font-bold text-slate-700">Age & Gender *</label>
                  <div className="flex gap-2 mt-1">
                    <input required type="number" className="w-1/2 p-2.5 border rounded-xl" placeholder="Age" value={newProfile.age} onChange={e => setNewProfile({...newProfile, age: e.target.value})} />
                    <select className="w-1/2 p-2.5 border rounded-xl" value={newProfile.gender} onChange={e => setNewProfile({...newProfile, gender: e.target.value})}>
                      <option value="Male">Male (Groom)</option>
                      <option value="Female">Female (Bride)</option>
                    </select>
                  </div>
                </div>
              </div>

              <div className="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label className="font-bold text-slate-700">Gotra *</label>
                  <input required type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="e.g. Chauhan / Parihar" value={newProfile.gotra} onChange={e => setNewProfile({...newProfile, gotra: e.target.value})} />
                </div>
                <div>
                  <label className="font-bold text-slate-700">City / Location *</label>
                  <input required type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="e.g. Indore" value={newProfile.city} onChange={e => setNewProfile({...newProfile, city: e.target.value})} />
                </div>
              </div>

              <div className="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label className="font-bold text-slate-700">Education</label>
                  <input type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="e.g. B.Tech / M.Com" value={newProfile.education} onChange={e => setNewProfile({...newProfile, education: e.target.value})} />
                </div>
                <div>
                  <label className="font-bold text-slate-700">Profession / Occupation</label>
                  <input type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="e.g. Software Engineer / Business" value={newProfile.profession} onChange={e => setNewProfile({...newProfile, profession: e.target.value})} />
                </div>
              </div>

              <div>
                <label className="font-bold text-slate-700">Family Details (Father, Mother, Siblings)</label>
                <textarea rows="2" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="Father occupation, mother, brothers, sisters..." value={newProfile.familyDetails} onChange={e => setNewProfile({...newProfile, familyDetails: e.target.value})} />
              </div>

              <div>
                <label className="font-bold text-slate-700">Contact Number *</label>
                <input required type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="+91 XXXXX XXXXX" value={newProfile.contact} onChange={e => setNewProfile({...newProfile, contact: e.target.value})} />
              </div>

              <div className="pt-2">
                <button type="submit" className="w-full bg-red-900 hover:bg-red-800 text-amber-100 font-bold py-3 rounded-xl shadow">
                  Submit & Publish Profile
                </button>
              </div>
            </form>
          </div>
        </div>
      )}

      {/* MODAL: ADD BUSINESS AD FORM */}
      {showAddAdModal && (
        <div className="fixed inset-0 z-50 bg-black/60 backdrop-blur-sm flex items-center justify-center p-4 overflow-y-auto">
          <div className="bg-white rounded-3xl max-w-xl w-full p-6 shadow-2xl border border-amber-300 relative my-8">
            <button 
              onClick={() => setShowAddAdModal(false)}
              className="absolute top-4 right-4 text-slate-400 hover:text-slate-600 p-1 rounded-full"
            >
              <X className="w-6 h-6" />
            </button>

            <h2 className="text-2xl font-serif font-bold text-red-950 mb-1">Advertise Your Business</h2>
            <p className="text-xs text-slate-500 mb-4">Promote your shop/service in the Rathore Samaj App directory.</p>

            <form onSubmit={handleAdSubmit} className="space-y-3 text-xs">
              <div>
                <label className="font-bold text-slate-700">Shop / Business Name *</label>
                <input required type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="e.g. Rathore Hardware & Electronics" value={newAd.title} onChange={e => setNewAd({...newAd, title: e.target.value})} />
              </div>

              <div className="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label className="font-bold text-slate-700">Owner Name *</label>
                  <input required type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="Owner Full Name" value={newAd.owner} onChange={e => setNewAd({...newAd, owner: e.target.value})} />
                </div>
                <div>
                  <label className="font-bold text-slate-700">Category</label>
                  <select className="w-full p-2.5 mt-1 border rounded-xl" value={newAd.category} onChange={e => setNewAd({...newAd, category: e.target.value})}>
                    <option value="Retail & Shopping">Retail & Shopping</option>
                    <option value="Hardware & Construction">Hardware & Construction</option>
                    <option value="Event & Catering">Event & Catering</option>
                    <option value="Medical & Health">Medical & Health</option>
                    <option value="Services">Services</option>
                  </select>
                </div>
              </div>

              <div>
                <label className="font-bold text-slate-700">Shop Tagline / Description *</label>
                <textarea required rows="2" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="Brief details of your products/services..." value={newAd.tagline} onChange={e => setNewAd({...newAd, tagline: e.target.value})} />
              </div>

              <div>
                <label className="font-bold text-slate-700">Special Offer for Samaj Members (Optional)</label>
                <input type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="e.g. 10% Discount for Rathore Samaj families" value={newAd.offer} onChange={e => setNewAd({...newAd, offer: e.target.value})} />
              </div>

              <div className="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label className="font-bold text-slate-700">Shop Address *</label>
                  <input required type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="Full shop address" value={newAd.address} onChange={e => setNewAd({...newAd, address: e.target.value})} />
                </div>
                <div>
                  <label className="font-bold text-slate-700">Contact Phone *</label>
                  <input required type="text" className="w-full p-2.5 mt-1 border rounded-xl" placeholder="+91 XXXXX XXXXX" value={newAd.phone} onChange={e => setNewAd({...newAd, phone: e.target.value})} />
                </div>
              </div>

              <div className="pt-2">
                <button type="submit" className="w-full bg-amber-500 hover:bg-amber-400 text-red-950 font-bold py-3 rounded-xl shadow">
                  Publish Business Advertisement
                </button>
              </div>
            </form>
          </div>
        </div>
      )}
    </div>
  );
}