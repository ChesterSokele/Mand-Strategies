import Navbar from "@/components/Navbar";
import HeroSection from "@/components/HeroSection";
import ServicesSection from "@/components/ServicesSection";
import FeaturedEngagement from "@/components/FeaturedEngagement";
import HowWeEngage from "@/components/HowWeEngage";
import GallerySection from "@/components/GallerySection";
import ReviewsSection from "@/components/ReviewsSection";
import WhyUsSection from "@/components/WhyUsSection";
import FAQSection from "@/components/FAQSection";
import CTASection from "@/components/CTASection";
import Footer from "@/components/Footer";

const Index = () => {
  return (
    <div className="min-h-screen">
      <Navbar />
      <HeroSection />
      <ServicesSection />
      <FeaturedEngagement />
      <HowWeEngage />
      <GallerySection />
      <WhyUsSection />
      <ReviewsSection />
      <FAQSection />
      <CTASection />
      <Footer />
    </div>
  );
};

export default Index;
