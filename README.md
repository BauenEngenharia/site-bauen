export default function BauenSite() {
  return (
    <main className="bg-black text-white min-h-screen font-sans">
      <header className="bg-yellow-400 text-black py-6 shadow-md">
        <div className="max-w-5xl mx-auto px-4">
          <h1 className="text-3xl font-bold">Bauen Engenharia e Arquitetura</h1>
          <p className="text-sm">Excelência em Projetos, Obras e Incorporações</p>
        </div>
      </header>

      <section className="max-w-5xl mx-auto px-4 py-10">
        <h2 className="text-2xl font-bold text-yellow-400 mb-4">Quem Somos</h2>
        <p className="text-gray-200">
          Com ampla experiência em obras públicas e privadas, a <strong>Bauen Engenharia e Arquitetura</strong> já entregou mais de <strong>R$ 15 milhões</strong> em obras públicas em todo o Brasil.
          Atuamos de forma completa, desde a <strong>concepção e administração da obra</strong> até os projetos técnicos e legalizações.
        </p>
      </section>

      <section className="bg-yellow-400 text-black py-10">
        <div className="max-w-5xl mx-auto px-4">
          <h2 className="text-2xl font-bold mb-4">Serviços</h2>
          <ul className="grid grid-cols-1 md:grid-cols-2 gap-4 text-lg">
            <li>Projetos Estruturais</li>
            <li>Projetos Elétricos e Hidrossanitários</li>
            <li>Projetos de Arquitetura</li>
            <li>Administração e Execução de Obras</li>
            <li>Laudos Técnicos e Requisições</li>
            <li>Protocolos de Alvarás</li>
            <li>Projetos de Incorporação</li>
          </ul>
        </div>
      </section>

      <section className="max-w-5xl mx-auto px-4 py-10">
        <h2 className="text-2xl font-bold text-yellow-400 mb-4">Atendimento</h2>
        <p className="text-gray-200">
          Com sede em <strong>Santa Catarina</strong>, prestamos serviços para todo o Brasil, oferecendo soluções personalizadas e com alto padrão técnico.
        </p>
      </section>

      <section className="bg-yellow-400 text-black py-10">
        <div className="max-w-5xl mx-auto px-4">
          <h2 className="text-2xl font-bold mb-4">Redes Sociais</h2>
          <ul className="space-y-2 text-lg">
            <li>
              Instagram: <a href="https://www.instagram.com/cleverson_bp" className="underline">@cleverson_bp</a>
            </li>
            <li>
              Instagram: <a href="https://www.instagram.com/bauenengenhariasbs" className="underline">@bauenengenhariasbs</a>
            </li>
          </ul>
        </div>
      </section>

      <footer className="bg-black text-gray-400 text-sm text-center py-4 border-t border-yellow-400">
        &copy; {new Date().getFullYear()} Bauen Engenharia e Arquitetura. Todos os direitos reservados.
      </footer>
    </main>
  );
}

