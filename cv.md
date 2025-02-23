import React from "react";

const Home = () => {
  return (
    <div className="min-h-screen bg-gray-900 text-white font-sans flex flex-col items-center py-10">
      {/* About Section */}
      <section className="p-10 text-center bg-white text-gray-900 shadow-xl rounded-lg w-11/12 max-w-3xl mb-10">
        <img
          src="/aul.jpg"
          alt="Profile"
          className="w-32 h-32 rounded-full mx-auto border-4 border-blue-500 shadow-lg"
        />
        <h1 className="text-4xl font-bold mt-4">Aulia Nur Ratri</h1>
        <p className="text-lg text-gray-600">Mahasiswa</p>
      </section>

      {/* Skills & Services Section */}
      <div className="grid grid-cols-1 md:grid-cols-2 gap-10 w-11/12 max-w-4xl mb-10">
        {/* Skills Section */}
        <section className="p-10 bg-gradient-to-r from-blue-500 to-indigo-600 rounded-lg shadow-lg border border-blue-300">
          <h2 className="text-2xl font-semibold mb-4 flex items-center">
            <span className="mr-2">💻</span> Skills
          </h2>
          <ul className="list-disc pl-5 text-lg">
            <li>Next.js</li>
            <li>React.js</li>
            <li>JavaScript</li>
            <li>SQL & Database Management</li>
          </ul>
        </section>

        {/* Services Section */}
        <section className="p-10 bg-gradient-to-r from-green-500 to-teal-600 text-gray-900 rounded-lg shadow-lg border border-green-300">
          <h2 className="text-2xl font-semibold mb-4 flex items-center">
            <span className="mr-2">🛠️</span> Services
          </h2>
          <ul className="list-disc pl-5 text-lg">
            <li>Website Development</li>
            <li>Database Management</li>
            <li>IT Training & Consulting</li>
          </ul>
        </section>
      </div>

      {/* Portfolio Section */}
      <section className="p-10 bg-gradient-to-r from-purple-500 to-pink-600 rounded-lg shadow-lg border border-purple-300 w-11/12 max-w-4xl mb-10">
        <h2 className="text-2xl font-semibold mb-4 flex items-center">
          <span className="mr-2">📁</span> Portfolios
        </h2>
        <p className="text-lg">Coming soon...</p>
      </section>

      {/* Contact Section */}
      <section className="p-10 bg-gradient-to-r from-red-500 to-orange-600 text-white text-center rounded-lg shadow-lg border border-red-300 w-11/12 max-w-4xl">
        <h2 className="text-2xl font-semibold mb-4 flex items-center justify-center">
          <span className="mr-2">📩</span> Contact
        </h2>
        <p className="text-lg">Email: iin@example.com</p>
        <p className="text-lg">LinkedIn: linkedin.com/in/iinsholihin</p>
      </section>
    </div>
  );
};

export default Home;
