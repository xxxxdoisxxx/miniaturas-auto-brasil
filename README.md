const DEFAULT_PRODUCTS = [
  {
    id: 'fusca',
    name: 'Volkswagen Fusca',
    category: 'classicos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Volkswagen',
    description: 'Miniatura clássica com acabamento premium, pintura detalhada e desenho fiel ao ícone nacional.',
    image: 'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1553440569-bcc63803a83d?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 1
  },
  {
    id: 'opala',
    name: 'Chevrolet Opala',
    category: 'classicos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Chevrolet',
    description: 'Modelo icônico dos anos 70 com detalhes de pintura e acabamento que lembram o melhor da era clássica.',
    image: 'https://images.unsplash.com/photo-1553440569-bcc63803a83d?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1553440569-bcc63803a83d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 2
  },
  {
    id: 'chevette',
    name: 'Chevrolet Chevette',
    category: 'classicos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Chevrolet',
    description: 'Miniatura representando o lendário compacto nacional, com linhas simples e presença marcante.',
    image: 'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1553440569-bcc63803a83d?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 3
  },
  {
    id: 'brasilia',
    name: 'Volkswagen Brasília',
    category: 'classicos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Volkswagen',
    description: 'Um clássico de design marcante, reproduzido com detalhes de pintura e acabamento premium.',
    image: 'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 4
  },
  {
    id: 'fiat-147',
    name: 'Fiat 147',
    category: 'classicos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Fiat',
    description: 'Miniatura do compacto que fez história, com atenção aos detalhes e visual muito fiel ao original.',
    image: 'https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1553440569-bcc63803a83d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 5
  },
  {
    id: 'santana',
    name: 'Volkswagen Santana',
    category: 'classicos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Volkswagen',
    description: 'Perfil elegante e presença de garagem, em uma miniatura premium para colecionadores.',
    image: 'https://images.unsplash.com/photo-1525609004556-c46c7d6cf023?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1525609004556-c46c7d6cf023?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 6
  },
  {
    id: 'gol',
    name: 'Volkswagen Gol',
    category: 'populares',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Volkswagen',
    description: 'Um dos carros mais populares do Brasil, celebrado em miniatura com acabamento refinado e dimensões perfeitas para colecionar.',
    image: 'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 7
  },
  {
    id: 'uno',
    name: 'Fiat Uno',
    category: 'populares',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Fiat',
    description: 'Miniatura do compacto nacional que conquistou milhares de brasileiros, com pintura e detalhes cuidadosos.',
    image: 'https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1553440569-bcc63803a83d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 8
  },
  {
    id: 'saveiro',
    name: 'Volkswagen Saveiro',
    category: 'populares',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Volkswagen',
    description: 'Representação do utilitário popular com linhas robustas e visual muito fiel ao modelo conhecido.',
    image: 'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 9
  },
  {
    id: 'corsa',
    name: 'Chevrolet Corsa',
    category: 'populares',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Chevrolet',
    description: 'Miniatura premium do hatch compacto, ideal para apaixonados por modelos que marcaram a rotina urbana.',
    image: 'https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1553440569-bcc63803a83d?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 10
  },
  {
    id: 'celta',
    name: 'Chevrolet Celta',
    category: 'populares',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Chevrolet',
    description: 'Detalhes refinados em miniatura com visual fiel ao popular modelo nacional.',
    image: 'https://images.unsplash.com/photo-1544636331-e26879cd4d9b?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1544636331-e26879cd4d9b?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 11
  },
  {
    id: 'astra',
    name: 'Chevrolet Astra',
    category: 'populares',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Chevrolet',
    description: 'Modelo urbano e sofisticado em miniatura desenvolvida para amantes de coleção premium.',
    image: 'https://images.unsplash.com/photo-1525609004556-c46c7d6cf023?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1525609004556-c46c7d6cf023?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 12
  },
  {
    id: 'golf',
    name: 'Volkswagen Golf',
    category: 'populares',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Volkswagen',
    description: 'A miniatura do hatch que marcou geração, mantendo o espírito esportivo e a presença premium.',
    image: 'https://images.unsplash.com/photo-1544636331-e26879cd4d9b?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1544636331-e26879cd4d9b?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1525609004556-c46c7d6cf023?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1553440569-bcc63803a83d?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 13
  },
  {
    id: 'palio',
    name: 'Fiat Palio',
    category: 'populares',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Fiat',
    description: 'Modelo clássico do mercado brasileiro com aparência refinada e detalhes de colecionador.',
    image: 'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 14
  },
  {
    id: 'mustang',
    name: 'Ford Mustang',
    category: 'esportivos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Ford',
    description: 'Miniatura do ícone americano com presença esportiva, design agressivo e acabamento premium.',
    image: 'https://images.unsplash.com/photo-1494905998402-395d579af36f?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1494905998402-395d579af36f?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1553440569-bcc63803a83d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 15
  },
  {
    id: 'camaro',
    name: 'Chevrolet Camaro',
    category: 'esportivos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Chevrolet',
    description: 'Uma miniatura para quem gosta de potência e estilo, com linhas esportivas e detalhes marcantes.',
    image: 'https://images.unsplash.com/photo-1503736334956-4c8f8e92946d?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1503736334956-4c8f8e92946d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 16
  },
  {
    id: 'skyline',
    name: 'Nissan Skyline',
    category: 'esportivos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Nissan',
    description: 'Um modelo lendário para colecionadores, com estética performática e acabamento profissional.',
    image: 'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1494905998402-395d579af36f?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1503736334956-4c8f8e92946d?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 17
  },
  {
    id: 'supra',
    name: 'Toyota Supra',
    category: 'esportivos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Toyota',
    description: 'Representação fiel do esportivo japonês que combina performance, cultura automotiva e presença visual.',
    image: 'https://images.unsplash.com/photo-1503736334956-4c8f8e92946d?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1503736334956-4c8f8e92946d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1494905998402-395d579af36f?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 18
  },
  {
    id: 'lamborghini',
    name: 'Lamborghini',
    category: 'esportivos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Lamborghini',
    description: 'Miniatura da referência italiana em performance, ocupando destaque na coleção premium.',
    image: 'https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1494905998402-395d579af36f?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1503736334956-4c8f8e92946d?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 19
  },
  {
    id: 'ferrari',
    name: 'Ferrari',
    category: 'esportivos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Ferrari',
    description: 'Modelo de alta performance e grande presença visual, representando o DNA esportivo da marca.',
    image: 'https://images.unsplash.com/photo-1544636331-e26879cd4d9b?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1544636331-e26879cd4d9b?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1503736334956-4c8f8e92946d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1494905998402-395d579af36f?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 20
  },
  {
    id: 'porsche',
    name: 'Porsche',
    category: 'esportivos',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Porsche',
    description: 'Desempenho, design refinado e exclusividade em uma miniatura premium para colecionadores.',
    image: 'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1503736334956-4c8f8e92946d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1494905998402-395d579af36f?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 21
  },
  {
    id: 's10',
    name: 'Chevrolet S10',
    category: 'utilitarios',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Chevrolet',
    description: 'Pickup robusta e moderna, com presença de colecionador e visual forte.',
    image: 'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 22
  },
  {
    id: 'ranger',
    name: 'Ford Ranger',
    category: 'utilitarios',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Ford',
    description: 'Uma miniatura de utilitário com visual robusto e detalhes que valorizam a linha premium.',
    image: 'https://images.unsplash.com/photo-1525609004556-c46c7d6cf023?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1525609004556-c46c7d6cf023?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 23
  },
  {
    id: 'hilux',
    name: 'Toyota Hilux',
    category: 'utilitarios',
    scale: '1:64',
    material: 'Metal',
    manufacturer: 'Toyota',
    description: 'Ícone da robustez, em minúscula escala com acabamento premium e presença memorável.',
    image: 'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1000&q=80',
    gallery: [
      'https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?auto=format&fit=crop&w=1000&q=80',
      'https://images.unsplash.com/photo-1525609004556-c46c7d6cf023?auto=format&fit=crop&w=1000&q=80'
    ],
    price: null,
    available: true,
    pixDiscountEnabled: true,
    popularity: 24
  }
];

const FALLBACK_REVIEWS = [
  {
    id: 'initial',
    name: 'Cliente autenticado',
    rating: 5,
    comment: 'Sua opinião ajuda nossa coleção a crescer! Seja um dos primeiros clientes a avaliar sua experiência com a Miniaturas Auto Brasil.',
    date: 'Aguardando avaliação'
  }
];

const APP_CONFIG = {
  whatsappNumber: '(15) 98808-6215',
  whatsappLink: 'https://wa.me/5515988086215',
  pixDiscountEnabled: true
};

const STORAGE_KEYS = {
  products: 'miniaturas-auto-brasil-products',
  reviews: 'miniaturas-auto-brasil-reviews',
  orders: 'miniaturas-auto-brasil-orders',
  config: 'miniaturas-auto-brasil-config',
  adminAuth: 'miniaturas-auto-brasil-admin-auth'
};

function loadState() {
  const savedProducts = JSON.parse(localStorage.getItem(STORAGE_KEYS.products) || 'null');
  const savedReviews = JSON.parse(localStorage.getItem(STORAGE_KEYS.reviews) || 'null');
  const savedOrders = JSON.parse(localStorage.getItem(STORAGE_KEYS.orders) || 'null');
  const savedConfig = JSON.parse(localStorage.getItem(STORAGE_KEYS.config) || 'null');

  return {
    products: Array.isArray(savedProducts) && savedProducts.length ? savedProducts : DEFAULT_PRODUCTS,
    reviews: Array.isArray(savedReviews) && savedReviews.length ? savedReviews : [],
    orders: Array.isArray(savedOrders) ? savedOrders : [],
    config: savedConfig || { ...APP_CONFIG }
  };
}

function ensureDefaultState() {
  const state = loadState();
  if (!localStorage.getItem(STORAGE_KEYS.products)) {
    localStorage.setItem(STORAGE_KEYS.products, JSON.stringify(DEFAULT_PRODUCTS));
  }
  if (!localStorage.getItem(STORAGE_KEYS.config)) {
    localStorage.setItem(STORAGE_KEYS.config, JSON.stringify(APP_CONFIG));
  }
  if (!localStorage.getItem(STORAGE_KEYS.reviews)) {
    localStorage.setItem(STORAGE_KEYS.reviews, JSON.stringify([]));
  }
  if (!localStorage.getItem(STORAGE_KEYS.orders)) {
    localStorage.setItem(STORAGE_KEYS.orders, JSON.stringify([]));
  }
  return state;
}

function formatPrice(value) {
  if (value === null || value === undefined || value === '') {
    return 'A COMBINAR';
  }
  return new Intl.NumberFormat('pt-BR', {
    style: 'currency',
    currency: 'BRL'
  }).format(Number(value));
}

function getPixPrice(price) {
  if (price === null || price === undefined || price === '') return null;
  return Number(price) * 0.95;
}

function productPriceInfo(product, useGlobalDiscount = true) {
  const productDiscountEnabled = product.pixDiscountEnabled !== undefined ? product.pixDiscountEnabled : true;
  const discountEnabled = useGlobalDiscount && productDiscountEnabled;

  if (product.price === null || product.price === undefined || product.price === '') {
    return {
      label: 'PREÇO A COMBINAR',
      original: null,
      pix: null,
      discountEnabled: false,
      message: 'Consulte disponibilidade, escala, acabamento e valor pelo WhatsApp.'
    };
  }

  const original = Number(product.price);
  const pix = discountEnabled ? getPixPrice(original) : null;
  return {
    label: formatPrice(original),
    original,
    pix,
    discountEnabled,
    message: 'Consulte disponibilidade, escala, acabamento e valor pelo WhatsApp.'
  };
}

function renderProductCard(product) {
  const priceInfo = productPriceInfo(product, true);
  const discountMarkup = priceInfo.pix
    ? `<div class="price-pix">Preço com Pix: <strong>${formatPrice(priceInfo.pix)}</strong></div>`
    : '';

  return `
    <article class="product-card" data-category="${product.category}">
      <div class="product-card-media">
        <img src="${product.image}" alt="${product.name}" loading="lazy" />
      </div>
      <div class="product-card-body">
        <div class="product-topline">
          <span>${product.scale || 'Escala à confirmar'}</span>
          <span>${product.material || 'Material à confirmar'}</span>
        </div>
        <h3>${product.name}</h3>
        <p>${product.description}</p>
        <div class="product-price">
          <span>${priceInfo.label}</span>
          ${discountMarkup}
          <small>Consulte disponibilidade, escala, acabamento e valor pelo WhatsApp.</small>
        </div>
        <div class="product-actions">
          <a href="product.html?id=${product.id}" class="btn btn-secondary">VER DETALHES</a>
          <a class="btn btn-whatsapp" href="https://wa.me/5515988086215?text=${encodeURIComponent(`Olá! Tenho interesse na miniatura ${product.name}. Gostaria de saber o preço, a escala disponível e as opções de entrega.`)}" target="_blank" rel="noopener noreferrer">CONSULTAR PELO WHATSAPP</a>
        </div>
      </div>
    </article>
  `;
}

function renderProducts(query = 'all') {
  const grid = document.getElementById('productGrid');
  if (!grid) return;

  const state = loadState();
  const filtered = query === 'all'
    ? state.products
    : state.products.filter(product => product.category === query);

  grid.innerHTML = filtered.map(renderProductCard).join('');
}

function attachCategoryFilters() {
  const filterButtons = document.querySelectorAll('.filter-btn');
  filterButtons.forEach(button => {
    button.addEventListener('click', () => {
      filterButtons.forEach(item => item.classList.toggle('active', item === button));
      renderProducts(button.dataset.filter);
    });
  });
}

function createStars(rating) {
  return Array.from({ length: 5 }, (_, index) => index < Number(rating) ? '★' : '☆').join('');
}

function renderReviews() {
  const reviewList = document.getElementById('reviewList');
  if (!reviewList) return;

  const state = loadState();
  const reviews = state.reviews.length ? state.reviews : FALLBACK_REVIEWS;

  reviewList.innerHTML = reviews.map(review => {
    if (review.comment.includes('Sua opinião ajuda nossa coleção a crescer')) {
      return `
        <div class="review-card empty-review">
          <div class="review-body">
            <p>${review.comment}</p>
          </div>
        </div>
      `;
    }

    return `
      <article class="review-card">
        <div class="review-top">
          <strong>${review.name}</strong>
          <span>${review.date}</span>
        </div>
        <div class="stars">${createStars(review.rating)}</div>
        <p>${review.comment}</p>
      </article>
    `;
  }).join('');
}

function handleCepLookup(inputId = 'cepHome', messageId = 'cepMessage') {
  const input = document.getElementById(inputId);
  const message = document.getElementById(messageId);
  if (!input || !message) return;

  const cleanCep = input.value.replace(/\D/g, '');
  if (cleanCep.length !== 8) {
    message.textContent = 'Informe um CEP válido.';
    return;
  }

  message.textContent = 'Consultando endereço...';

  fetch(`https://viacep.com.br/ws/${cleanCep}/json/`)
    .then(response => response.json())
    .then(data => {
      if (data.erro) {
        message.textContent = 'CEP não encontrado. Consulte o valor e o prazo pelo WhatsApp.';
        return;
      }

      const orderForm = document.getElementById('orderForm');
      if (orderForm) {
        document.getElementById('cep').value = cleanCep;
        document.getElementById('cidade').value = data.localidade || '';
        document.getElementById('estado').value = data.uf || '';
        document.getElementById('rua').value = data.logradouro || '';
        document.getElementById('bairro').value = data.bairro || '';
      }

      message.textContent = `Endereço localizado em ${data.localidade} - ${data.uf}. Consulte o valor e o prazo de entrega pelo WhatsApp.`;
    })
    .catch(() => {
      message.textContent = 'Não foi possível consultar o CEP neste momento. Consulte o valor e o prazo pelo WhatsApp.';
    });
}

function openOrderModal(productId = null) {
  const modal = document.getElementById('orderModal');
  const form = document.getElementById('orderForm');
  const state = loadState();
  const product = productId ? state.products.find(item => item.id === productId) : null;

  if (!modal) return;

  if (product) {
    const productName = document.getElementById('miniaturaNome');
    const scale = document.getElementById('escalaPedido');
    if (productName) productName.value = product.name;
    if (scale) scale.value = product.scale || '';
  }

  if (form) {
    form.reset();
    const qty = document.getElementById('quantidade');
    if (qty) qty.value = 1;
    const productName = document.getElementById('miniaturaNome');
    if (product && productName) productName.value = product.name;
    const scale = document.getElementById('escalaPedido');
    if (product && scale) scale.value = product.scale || '';
  }

  modal.classList.remove('hidden');
}

function closeOrderModal() {
  const modal = document.getElementById('orderModal');
  if (modal) modal.classList.add('hidden');
}

function attachOrderModalEvents() {
  const modal = document.getElementById('orderModal');
  if (!modal) return;

  modal.querySelectorAll('[data-close="true"]').forEach(item => {
    item.addEventListener('click', closeOrderModal);
  });

  const form = document.getElementById('orderForm');
  if (!form) return;

  form.addEventListener('submit', event => {
    event.preventDefault();

    const requiredFields = [
      'clienteNome',
      'clienteWhats',
      'cep',
      'estado',
      'cidade',
      'bairro',
      'rua',
      'numero',
      'miniaturaNome',
      'quantidade',
      'formaPagamento'
    ];

    const invalid = requiredFields.find(field => !document.getElementById(field).value.trim());
    const privacy = document.getElementById('privacyCheck');

    if (invalid) {
      alert('Por favor, preencha todos os campos obrigatórios.');
      return;
    }

    if (!privacy.checked) {
      alert('Você precisa confirmar que leu a política de privacidade.');
      return;
    }

    const state = loadState();
    const order = {
      id: crypto.randomUUID ? crypto.randomUUID() : Date.now().toString(),
      createdAt: new Date().toISOString(),
      clienteNome: document.getElementById('clienteNome').value.trim(),
      clienteWhats: document.getElementById('clienteWhats').value.trim(),
      cep: document.getElementById('cep').value.trim(),
      estado: document.getElementById('estado').value.trim(),
      cidade: document.getElementById('cidade').value.trim(),
      bairro: document.getElementById('bairro').value.trim(),
      rua: document.getElementById('rua').value.trim(),
      numero: document.getElementById('numero').value.trim(),
      complemento: document.getElementById('complemento').value.trim(),
      miniatura: document.getElementById('miniaturaNome').value.trim(),
      quantidade: document.getElementById('quantidade').value.trim(),
      escala: document.getElementById('escalaPedido').value.trim(),
      observacoes: document.getElementById('observacoes').value.trim(),
      formaPagamento: document.getElementById('formaPagamento').value.trim(),
      status: 'novo'
    };

    state.orders.push(order);
    localStorage.setItem(STORAGE_KEYS.orders, JSON.stringify(state.orders));

    const message = [
      'Olá! Vim pelo site Miniaturas Auto Brasil e gostaria de fazer um pedido.',
      '',
      'DADOS DO CLIENTE:',
      `Nome: ${order.clienteNome}`,
      `WhatsApp: ${order.clienteWhats}`,
      '',
      'ENDEREÇO:',
      `CEP: ${order.cep}`,
      `Rua: ${order.rua}`,
      `Número: ${order.numero}`,
      `Bairro: ${order.bairro}`,
      `Cidade: ${order.cidade}`,
      `Estado: ${order.estado}`,
      '',
      'PRODUTO:',
      `Miniatura: ${order.miniatura}`,
      `Quantidade: ${order.quantidade}`,
      `Escala: ${order.escala || 'Não informada'}`,
      '',
      'PREÇO: A COMBINAR',
      'Frete: A CONSULTAR',
      '',
      'FORMA DE PAGAMENTO PREFERIDA:',
      order.formaPagamento,
      '',
      'Tenho interesse no desconto de 5% para pagamento via Pix, caso aplicável.',
      '',
      'Gostaria de confirmar a disponibilidade, o preço final, o frete e as condições de pagamento.',
      '',
      'Obrigado!'
    ].join('\n');

    const waLink = `${APP_CONFIG.whatsappLink}?text=${encodeURIComponent(message)}`;
    window.open(waLink, '_blank');
    closeOrderModal();
    alert('Pedido preparado para envio pelo WhatsApp. Confirme a mensagem para concluir o atendimento.');
  });
});

function renderProductDetail() {
  const container = document.getElementById('productDetail');
  if (!container) return;

  const params = new URLSearchParams(window.location.search);
  const productId = params.get('id');
  const state = loadState();
  const product = state.products.find(item => item.id === productId) || state.products[0];

  if (!product) {
    container.innerHTML = '<div class="empty-state">Produto não encontrado.</div>';
    return;
  }

  const priceInfo = productPriceInfo(product, true);
  const mainImage = product.gallery?.[0] || product.image;

  container.innerHTML = `
    <div class="product-detail-card">
      <div class="product-gallery">
        <div class="main-gallery">
          <img src="${mainImage}" alt="${product.name}" />
        </div>
        <div class="thumbs">
          ${(product.gallery || [product.image]).map((item, index) => `
            <button type="button" class="thumb ${index === 0 ? 'active' : ''}" data-src="${item}">
              <img src="${item}" alt="${product.name} ângulo ${index + 1}" />
            </button>
          `).join('')}
        </div>
      </div>

      <div class="product-info">
        <span class="eyebrow dark">${product.category}</span>
        <h1>${product.name}</h1>
        <div class="detail-meta">
          <span>Escala: ${product.scale || 'Consultar'}</span>
          <span>Material: ${product.material || 'Consultar'}</span>
          <span>Fabricante: ${product.manufacturer || 'Consultar'}</span>
        </div>
        <div class="price-box">
          <span class="price-label">${priceInfo.label}</span>
          ${priceInfo.pix ? `<span class="pix-tag">Pix: ${formatPrice(priceInfo.pix)}</span>` : '<span class="pix-tag no-discount">Desconto Pix não aplicado</span>'}
          <small>Consulte disponibilidade, escala, acabamento e valor pelo WhatsApp.</small>
        </div>

        <p class="product-description">${product.description}</p>

        <div class="quantity-form">
          <label for="productQty">Quantidade</label>
          <input id="productQty" type="number" min="1" value="1" />
        </div>

        <div class="cep-inline">
          <label for="productCep">CEP</label>
          <div class="cep-row">
            <input id="productCep" type="text" placeholder="Ex.: 01000-000" />
            <button type="button" id="productCepBtn" class="btn btn-secondary">Consultar</button>
          </div>
          <small id="productCepMessage">Consulte o valor e o prazo de entrega pelo WhatsApp.</small>
        </div>

        <div class="detail-actions">
          <button class="btn btn-primary" data-buy-product="${product.id}">COMPRAR AGORA</button>
          <a class="btn btn-whatsapp" href="https://wa.me/5515988086215?text=${encodeURIComponent(`Olá! Tenho interesse na miniatura ${product.name}. Gostaria de saber o preço, a escala disponível e as opções de entrega.`)}" target="_blank" rel="noopener noreferrer">CONSULTAR PELO WHATSAPP</a>
        </div>

        <div class="spec-list">
          <h3>Detalhes da miniatura</h3>
          <ul>
            <li><strong>Escala:</strong> ${product.scale || 'Consultar'}</li>
            <li><strong>Material:</strong> ${product.material || 'Consultar'}</li>
            <li><strong>Fabricante:</strong> ${product.manufacturer || 'Consultar'}</li>
            <li><strong>Detalhes da pintura:</strong> Acabamento premium com atenção ao visual realista.</li>
            <li><strong>Acabamento:</strong> Superfície refinada com pintura e detalhes reproduzidos.</li>
            <li><strong>Portas/capô/porta-malas:</strong> Aplicável conforme a referência do modelo.</li>
          </ul>
        </div>
      </div>
    </div>
  `;

  const mainGalleryImage = document.querySelector('.main-gallery img');
  document.querySelectorAll('.thumb').forEach(button => {
    button.addEventListener('click', () => {
      const src = button.dataset.src;
      if (mainGalleryImage) mainGalleryImage.src = src;
      document.querySelectorAll('.thumb').forEach(item => item.classList.toggle('active', item === button));
    });
  });

  const buyButton = document.querySelector('[data-buy-product]');
  if (buyButton) {
    buyButton.addEventListener('click', () => {
      openOrderModal(product.id);
      const quantityField = document.getElementById('quantidade');
      if (quantityField) quantityField.value = document.getElementById('productQty')?.value || 1;
    });
  }

  const cepButton = document.getElementById('productCepBtn');
  if (cepButton) {
    cepButton.addEventListener('click', () => {
      const cepInput = document.getElementById('productCep');
      const message = document.getElementById('productCepMessage');
      if (!cepInput || !message) return;
      const cleanCep = cepInput.value.replace(/\D/g, '');
      if (cleanCep.length !== 8) {
        message.textContent = 'Informe um CEP válido.';
        return;
      }

      fetch(`https://viacep.com.br/ws/${cleanCep}/json/`)
        .then(response => response.json())
        .then(data => {
          if (data.erro) {
            message.textContent = 'CEP não encontrado. Consulte o valor e o prazo pelo WhatsApp.';
            return;
          }
          message.textContent = `Endereço localizado em ${data.localidade} - ${data.uf}. Consulte o valor e o prazo pelo WhatsApp.`;
        })
        .catch(() => {
          message.textContent = 'Não foi possível consultar o CEP neste momento. Consulte o valor e o prazo pelo WhatsApp.';
        });
    });
  }
}

function initAdmin() {
  const loginSection = document.getElementById('adminLogin');
  const dashboard = document.getElementById('adminDashboard');
  const loginForm = document.getElementById('loginForm');
  const logoutBtn = document.getElementById('logoutBtn');

  const isAuthenticated = localStorage.getItem(STORAGE_KEYS.adminAuth) === 'true';
  if (isAuthenticated) {
    loginSection.classList.add('hidden');
    dashboard.classList.remove('hidden');
  }

  if (loginForm) {
    loginForm.addEventListener('submit', event => {
      event.preventDefault();
      const email = document.getElementById('adminEmail').value.trim();
      const password = document.getElementById('adminPassword').value.trim();

      if (email === 'admin@miniaturasautobrasil.com' && password === 'miniaturas123') {
        localStorage.setItem(STORAGE_KEYS.adminAuth, 'true');
        loginSection.classList.add('hidden');
        dashboard.classList.remove('hidden');
      } else {
        alert('Credenciais inválidas.');
      }
    });
  }

  if (logoutBtn) {
    logoutBtn.addEventListener('click', () => {
      localStorage.removeItem(STORAGE_KEYS.adminAuth);
      loginSection.classList.remove('hidden');
      dashboard.classList.add('hidden');
    });
  }

  const productForm = document.getElementById('productForm');
  if (productForm) {
    productForm.addEventListener('submit', event => {
      event.preventDefault();
      const id = document.getElementById('productId').value.trim();
      const name = document.getElementById('productName').value.trim();
      const category = document.getElementById('productCategory').value;
      const scale = document.getElementById('productScale').value.trim();
      const material = document.getElementById('productMaterial').value.trim();
      const price = document.getElementById('productPrice').value.trim();
      const image = document.getElementById('productImage').value.trim();
      const description = document.getElementById('productDescription').value.trim();
      const pixDiscountEnabled = document.getElementById('productPixDiscount').checked;

      const state = loadState();
      const existingIndex = state.products.findIndex(item => item.id === id);
      const productData = {
        id,
        name,
        category,
        scale: scale || '1:64',
        material: material || 'Metal',
        manufacturer: name.includes('Volkswagen') ? 'Volkswagen' : name.includes('Fiat') ? 'Fiat' : name.includes('Chevrolet') ? 'Chevrolet' : 'Fabricante',
        description,
        image,
        gallery: [image, image, image],
        price: price ? Number(price) : null,
        available: true,
        pixDiscountEnabled,
        popularity: existingIndex >= 0 ? state.products[existingIndex].popularity : Date.now()
      };

      if (existingIndex >= 0) {
        state.products[existingIndex] = productData;
      } else {
        state.products.push(productData);
      }

      localStorage.setItem(STORAGE_KEYS.products, JSON.stringify(state.products));
      alert('Produto salvo com sucesso.');
      productForm.reset();
    });
  }

  const configWhats = document.getElementById('configWhats');
  const configLink = document.getElementById('configLink');
  const globalPixDiscount = document.getElementById('globalPixDiscount');

  if (configWhats && configLink && globalPixDiscount) {
    const state = loadState();
    configWhats.value = state.config.whatsappNumber || '(15) 98808-6215';
    configLink.value = state.config.whatsappLink || 'https://wa.me/5515988086215';
    globalPixDiscount.checked = state.config.pixDiscountEnabled !== false;
  }

  const saveConfigBtn = document.getElementById('saveConfigBtn');
  if (saveConfigBtn) {
    saveConfigBtn.addEventListener('click', () => {
      const state = loadState();
      state.config.whatsappNumber = configWhats.value.trim() || '(15) 98808-6215';
      state.config.whatsappLink = configLink.value.trim() || 'https://wa.me/5515988086215';
      state.config.pixDiscountEnabled = globalPixDiscount.checked;
      localStorage.setItem(STORAGE_KEYS.config, JSON.stringify(state.config));
      alert('Configurações salvas.');
    });
  }

  const reviewForm = document.getElementById('reviewForm');
  if (reviewForm) {
    reviewForm.addEventListener('submit', event => {
      event.preventDefault();
      const state = loadState();
      const review = {
        id: crypto.randomUUID ? crypto.randomUUID() : Date.now().toString(),
        name: document.getElementById('reviewName').value.trim(),
        rating: Number(document.getElementById('reviewRating').value),
        comment: document.getElementById('reviewComment').value.trim(),
        date: new Date().toLocaleDateString('pt-BR')
      };
      state.reviews.push(review);
      localStorage.setItem(STORAGE_KEYS.reviews, JSON.stringify(state.reviews));
      alert('Avaliação cadastrada com sucesso.');
      reviewForm.reset();
      renderReviews();
    });
  }

  const ordersList = document.getElementById('ordersList');
  if (ordersList) {
    const state = loadState();
    ordersList.innerHTML = state.orders.length
      ? state.orders.map(order => `
          <div class="order-item">
            <strong>${order.miniatura}</strong>
            <span>${order.clienteNome} • ${order.formaPagamento}</span>
            <small>${new Date(order.createdAt).toLocaleString('pt-BR')}</small>
          </div>
        `).join('')
      : '<p>Nenhum pedido cadastrado ainda.</p>';
  }
}

function initHomePage() {
  ensureDefaultState();
  attachCategoryFilters();
  renderProducts();
  renderReviews();

  const cepBtn = document.getElementById('consultCepBtn');
  if (cepBtn) {
    cepBtn.addEventListener('click', () => handleCepLookup('cepHome', 'cepMessage'));
  }

  document.querySelectorAll('[data-buy-product]').forEach(button => {
    button.addEventListener('click', () => openOrderModal(button.dataset.buyProduct));
  });

  attachOrderModalEvents();

  const productCards = document.querySelectorAll('.product-card');
  productCards.forEach(card => {
    card.addEventListener('click', (event) => {
      if (event.target.closest('a')) return;
      const link = card.querySelector('a');
      if (link) window.location.href = link.href;
    });
  });
}

function initProductPage() {
  ensureDefaultState();
  renderProductDetail();
  attachOrderModalEvents();
  const productCepBtn = document.getElementById('productCepBtn');
  if (productCepBtn) {
    productCepBtn.addEventListener('click', () => handleCepLookup('productCep', 'productCepMessage'));
  }
}

function init() {
  const page = document.body.dataset.page;
  if (page === 'home') initHomePage();
  if (page === 'product') initProductPage();
  if (page === 'admin') initAdmin();
}

document.addEventListener('DOMContentLoaded', init);
