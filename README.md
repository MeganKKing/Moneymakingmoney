# Moneymakingmoney
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Input } from "@/components/ui/input";
import { Textarea } from "@/components/ui/textarea";

export default function FinancialServicesHome() {
  return (
    <div className="p-6 space-y-10">
      {/* Hero Section */}
      <section className="text-center space-y-4">
        <h1 className="text-4xl font-bold">Build Wealth. Protect Your Future. Empower Your Family.</h1>
        <p className="text-lg">Personalized financial strategies to eliminate debt, grow wealth, and secure your retirement.</p>
        <Button>Book a Free Consultation</Button>
      </section>

      {/* About Us Section */}
      <section className="space-y-4">
        <h2 className="text-3xl font-semibold">About Us</h2>
        <p>At our agency, we believe that financial education is the foundation of freedom. We are on a mission to empower individuals and families through strategies that help them get out of debt, build lasting wealth, and protect what matters most—their future.</p>
        <div className="grid md:grid-cols-2 gap-4">
          <Card>
            <CardContent className="space-y-2 p-4">
              <h3 className="text-xl font-semibold">Zhana Johnson</h3>
              <p>Zhana has a long-standing background in the insurance industry and a deep passion for helping others understand the power of insurance. She is committed to educating individuals on how to get out of debt, build wealth, and protect their retirement. She’s also growing her agency with like-minded professionals who share her passion.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="space-y-2 p-4">
              <h3 className="text-xl font-semibold">Megan Simons</h3>
              <p>Megan brings a wealth of experience in insurance and financial education. She’s passionate about simplifying complex financial concepts and guiding clients toward financial empowerment. She also plays a key role in expanding the agency’s mission and team.</p>
            </CardContent>
          </Card>
        </div>
      </section>

      {/* Services Section */}
      <section className="space-y-4">
        <h2 className="text-3xl font-semibold">Our Services</h2>
        <ul className="list-disc list-inside space-y-2">
          <li>Debt Elimination Strategies</li>
          <li>Retirement Protection Planning</li>
          <li>Insurance Education & Coverage Reviews</li>
          <li>Wealth-Building Through Safe Money Concepts</li>
          <li>Financial Literacy Workshops & Seminars</li>
        </ul>
      </section>

      {/* Learn Section */}
      <section className="space-y-4">
        <h2 className="text-3xl font-semibold">Learn</h2>
        <p>Explore tools, tips, and resources to grow your financial literacy.</p>
        <ul className="list-disc list-inside space-y-2">
          <li>What’s Your Financial Independence Number?</li>
          <li>Rule of 72 Explained</li>
          <li>Types of Insurance: Term vs. Cash Value</li>
          <li>Budget Templates and Retirement Calculators</li>
        </ul>
      </section>

      {/* Join Our Team Section */}
      <section className="space-y-4">
        <h2 className="text-3xl font-semibold">Join Our Team</h2>
        <p>We’re looking for driven individuals who share our mission to transform lives through financial education and empowerment. Ready to make a difference?</p>
        <Button>Apply Now</Button>
      </section>

      {/* Calendly Booking Section */}
      <section className="space-y-4">
        <h2 className="text-3xl font-semibold">Schedule a Meeting</h2>
        <p>Book a free consultation with one of our financial professionals through the embedded Calendly calendar below.</p>
        <div className="w-full h-[700px]">
          <iframe
            src="[https://calendly.com/megansimons/financial-analysis-review]"
            width="100%"
            height="100%"
            frameBorder="0"
            title="Schedule with Calendly"
          ></iframe>
        </div>
      </section>

      {/* Contact Section */}
      <section className="space-y-4">
        <h2 className="text-3xl font-semibold">Contact Us</h2>
        <form className="space-y-4 max-w-xl">
          <Input placeholder="Your Name" />
          <Input placeholder="Email Address" type="email" />
          <Textarea placeholder="How can we help you?" />
          <Button type="submit">Send Message</Button>
        </form>
      </section>
    </div>
  );
}
