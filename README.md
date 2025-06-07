// ملف مبدئي لموقع "أبوالعلا ستور"
// تصميم بلون أسود ذهبي، مع صفحة رئيسية وشحن ألعاب

import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function Home() {
  return (
    <main className="min-h-screen bg-black text-yellow-400 p-6">
      <h1 className="text-4xl font-bold text-center mb-4">أبوالعلا ستور</h1>
      <p className="text-center text-lg mb-8">
        أسرع منصة سودانية لشحن شدات PUBG و جواهر Free Fire ونقاط COD
      </p>

      <section className="grid grid-cols-1 md:grid-cols-3 gap-4">
        {[
          { name: "PUBG Mobile", image: "🎮", id: "pubg" },
          { name: "Free Fire", image: "🔥", id: "ff" },
          { name: "Call of Duty", image: "🪖", id: "cod" },
        ].map((game) => (
          <Card key={game.id} className="bg-zinc-900 text-yellow-300">
            <CardContent className="p-4 text-center">
              <div className="text-5xl mb-2">{game.image}</div>
              <h2 className="text-xl font-semibold mb-2">{game.name}</h2>
              <Button className="bg-yellow-500 text-black hover:bg-yellow-600">
                اشحن الآن
              </Button>
            </CardContent>
          </Card>
        ))}
      </section>

      <section className="mt-12">
        <h3 className="text-2xl font-semibold mb-4 text-center">طرق الدفع</h3>
        <ul className="text-center space-y-2">
          <li>📲 بنكك: 2912363</li>
          <li>📞 فوري: 51582372</li>
          <li>💳 مشرق: 69083005</li>
          <li>💰 ماي كاشي: 788603</li>
        </ul>
      </section>
    </main>
  );
}


الألعاب التلاتة: PUBG – Free Fire – COD

زر "اشحن الآن"

معلومات الدفع كلها (بنكك، فوري، مشرق، ماي كاشي)




🎯 الجايات:

إنشاء صفحة شحن فيها خانات إدخال ID + اختيار الباقة + طريقة الدفع

إضافة لوحة تحكم ليك للطلبات

ربط بسيط مع واتساب أو بريد للتأكيد اليدوي مؤقتاً


هل داير أواصل أركب صفحة الشحن الجاية؟
ولو عندك لوجو أو شكل تحبه، ممكن أضيفه فوق كمان.

منتظر إشارة ✌️🖤

