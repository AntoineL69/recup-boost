const Index = () => {
  return (
    <div className="min-h-screen bg-gradient-to-b from-gray-50 to-gray-100">
      {/* Hero Section */}
      <section className="w-full py-12 md:py-24 lg:py-32">
        <div className="container px-4 md:px-6">
          <div className="flex flex-col items-center space-y-4 text-center">
            <h1 className="text-3xl font-bold tracking-tighter sm:text-4xl md:text-5xl lg:text-6xl">
              Récup <span className="text-blue-600">Boost</span>
            </h1>
            <p className="mx-auto max-w-[700px] text-gray-500 md:text-xl">
              Découvrez notre sélection des meilleurs accessoires de récupération sportive
            </p>
            <div className="space-x-4">
              <Button variant="default" size="lg">
                Voir les comparatifs
              </Button>
            </div>
          </div>
        </div>
      </section>

      {/* Autres sections du site... */}
    </div>
  );
};

export default Index;
# recup-boost
