"use client";
import { useState } from "react";

export default function CVWizard() {
  const [step, setStep] = useState(1);

  const [formData, setFormData] = useState({
    name: "",
    email: "",
    phone: "",
    experiences: [""],
    skills: [""],
  });

  function nextStep() {
    setStep((s) => Math.min(s + 1, 4));
  }

  function prevStep() {
    setStep((s) => Math.max(s - 1, 1));
  }

  return (
    <div style={{ maxWidth: 500, margin: "auto", padding: 20 }}>
      <h1>منصة السيرة الذاتية</h1>
      <p>الخطوة {step} من 4</p>

      {step === 1 && (
        <>
          <input
            placeholder="الاسم"
            value={formData.name}
            onChange={(e) =>
              setFormData({ ...formData, name: e.target.value })
            }
          />
          <input
            placeholder="البريد الإلكتروني"
            value={formData.email}
            onChange={(e) =>
              setFormData({ ...formData, email: e.target.value })
            }
          />
          <input
            placeholder="رقم الهاتف"
            value={formData.phone}
            onChange={(e) =>
              setFormData({ ...formData, phone: e.target.value })
            }
          />
        </>
      )}

      {step === 2 && (
        <>
          <textarea
            placeholder="أدخل خبراتك"
            value={formData.experiences.join("\n")}
            onChange={(e) =>
              setFormData({
                ...formData,
                experiences: e.target.value.split("\n"),
              })
            }
          />
        </>
      )}

      {step === 3 && (
        <>
          <textarea
            placeholder="أدخل مهاراتك"
            value={formData.skills.join("\n")}
            onChange={(e) =>
              setFormData({
                ...formData,
                skills: e.target.value.split("\n"),
              })
            }
          />
        </>
      )}

      {step === 4 && (
        <div>
          <h2>المعاينة</h2>
          <p><b>الاسم:</b> {formData.name}</p>
          <p><b>البريد:</b> {formData.email}</p>
          <p><b>الهاتف:</b> {formData.phone}</p>
          <h3>الخبرات:</h3>
          <ul>
            {formData.experiences.map((exp, i) => (
              <li key={i}>{exp}</li>
            ))}
          </ul>
          <h3>المهارات:</h3>
          <ul>
            {formData.skills.map((sk, i) => (
              <li key={i}>{sk}</li>
            ))}
          </ul>
        </div>
      )}

      <div style={{ marginTop: 20 }}>
        {step > 1 && <button onClick={prevStep}>السابق</button>}
        {step < 4 && <button onClick={nextStep}>التالي</button>}
        {step === 4 && <button onClick={() => alert("تم الحفظ (تجريبي)")}>
          حفظ
        </button>}
      </div>
    </div>
  );
}
