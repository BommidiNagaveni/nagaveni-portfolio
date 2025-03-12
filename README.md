import React from "react";
import { Card } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { FaLinkedin, FaEnvelope, FaGlobe } from "react-icons/fa";

const Portfolio = () => {
  return (
    <div className="min-h-screen bg-gray-100 p-6 flex flex-col items-center">
      <Card className="max-w-4xl w-full bg-white p-6 rounded-2xl shadow-lg">
        <h1 className="text-3xl font-bold text-center">Nagaveni Bommidi</h1>
        <p className="text-center text-gray-600">Strategic Thinker | Business Operations | SaaS GTM</p>
        
        <div className="flex justify-center gap-4 mt-4">
          <Button variant="outline" size="icon" asChild>
            <a href="mailto:bommidinagaveni52@gmail.com" target="_blank" rel="noopener noreferrer">
              <FaEnvelope className="text-xl" />
            </a>
          </Button>
          <Button variant="outline" size="icon" asChild>
            <a href="https://linkedin.com/in/yourprofile" target="_blank" rel="noopener noreferrer">
              <FaLinkedin className="text-xl" />
            </a>
          </Button>
          <Button variant="outline" size="icon" asChild>
            <a href="https://yourwebsite.com" target="_blank" rel="noopener noreferrer">
              <FaGlobe className="text-xl" />
            </a>
          </Button>
        </div>

        <section className="mt-6">
          <h2 className="text-xl font-bold">About Me</h2>
          <p className="text-gray-700 mt-2">
            I am a strategic leader specializing in business operations, SaaS GTM, and marketing. As Co-Founder & COO of Omni DataX, I have led multiple high-impact projects driving business growth.
          </p>
        </section>

        <section className="mt-6">
          <h2 className="text-xl font-bold">Key Skills</h2>
          <ul className="list-disc list-inside text-gray-700 mt-2">
            <li>Business Operations & Strategy</li>
            <li>Marketing & Lead Generation</li>
            <li>Data Analytics & Cloud Computing</li>
            <li>Social Media & Content Creation</li>
            <li>Event Management & Brand Collaboration</li>
          </ul>
        </section>

        <section className="mt-6">
          <h2 className="text-xl font-bold">Major Projects</h2>
          <p className="text-gray-700 mt-2"><strong>Peep.Check:</strong> Developed GTM strategy for SaaS product ensuring transparency in education.</p>
          <p className="text-gray-700 mt-2"><strong>Omni DataX:</strong> Generated Rs 5 Cr in business leads, fostering an innovative workplace culture.</p>
          <p className="text-gray-700 mt-2"><strong>Ideas to Impacts Hub:</strong> Organized startup networking events under Startup India Incubation.</p>
        </section>

        <section className="mt-6">
          <h2 className="text-xl font-bold">Education & Certifications</h2>
          <ul className="list-disc list-inside text-gray-700 mt-2">
            <li>B.Tech in Computer Science Engineering</li>
            <li>Microsoft Azure & AWS Fundamentals</li>
            <li>TrendyTech Data Analytics & Cloud Computing</li>
          </ul>
        </section>
      </Card>
    </div>
  );
};

export default Portfolio;
