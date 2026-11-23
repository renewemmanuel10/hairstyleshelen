   <section
          class="w-full bg-surface py-16 lg:py-24"
          id="reserve-concierge"
        >
          <div
            class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-tablet lg:px-margin"
          >
            <div
              class="rounded-3xl bg-inverse-surface text-inverse-on-surface p-8 md:p-14 lg:p-20 relative overflow-hidden shadow-2xl border border-primary/20"
            >
              <!-- Ambient Glow Decor -->
              <div
                class="absolute -right-20 -top-20 w-96 h-96 rounded-full bg-primary/10 blur-3xl pointer-events-none"
              ></div>
              <div
                class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center relative z-10"
              >
                <!-- Left Column Copy -->
                <div class="lg:col-span-5 flex flex-col">
                  <div class="inline-flex items-center gap-2 mb-4">
                    <span
                      class="material-symbols-outlined text-primary-container text-[20px]"
                      >hotel_class</span
                    >
                    <span
                      class="font-label-caps text-label-caps text-primary-container uppercase tracking-[0.25em]"
                      >Private Suite Reservation</span
                    >
                  </div>
                  <h2
                    class="font-headline-lg text-headline-lg text-surface mb-6"
                  >
                    Ready for Your Next Signature Look?
                  </h2>
                  <p
                    class="font-body-lg text-body-lg text-surface-variant/80 mb-8 leading-relaxed"
                  >
                    Reserve your private suite session today. In order to
                    preserve the unhurried atmosphere and intimacy of our craft,
                    slots are released on a rolling fortnightly schedule.
                  </p>
                  <div
                    class="flex flex-col gap-3 font-body-sm text-body-sm text-surface-variant/70"
                  >
                    <div class="flex items-center gap-3">
                      <span
                        class="material-symbols-outlined text-primary-container text-[18px]"
                        >check_circle</span
                      >
                      <span
                        >Complimentary trichology scalp mapping with every
                        booking</span
                      >
                    </div>
                    <div class="flex items-center gap-3">
                      <span
                        class="material-symbols-outlined text-primary-container text-[18px]"
                        >check_circle</span
                      >
                      <span
                        >Full access to private beverage concierge &amp;
                        streaming suites</span
                      >
                    </div>
                    <div class="flex items-center gap-3">
                      <span
                        class="material-symbols-outlined text-primary-container text-[18px]"
                        >check_circle</span
                      >
                      <span
                        >Custom color blending &amp; hair extension sourcing
                        included</span
                      >
                    </div>
                  </div>
                </div>
                <!-- Right Column: Interactive Booking Widget -->
                <div
                  class="lg:col-span-7 bg-surface-container-lowest text-on-surface p-8 sm:p-10 rounded-2xl shadow-2xl border border-outline-variant/30"
                >
                  <h3
                    class="font-headline-sm text-headline-sm text-on-surface mb-2"
                  >
                    Direct Concierge Booking
                  </h3>
                  <p
                    class="font-body-sm text-body-sm text-on-surface-variant mb-8"
                  >
                    Select your preferences to preview immediate availability.
                  </p>
                  <form
                    class="grid grid-cols-1 sm:grid-cols-2 gap-5"
                    onsubmit="
                      event.preventDefault();
                      alert(
                        'Thank you. An atelier concierge will contact you within 2 business hours.',
                      );
                    "
                  >
                    <div class="flex flex-col gap-2">
                      <label
                        class="font-label-caps text-label-caps text-on-surface uppercase tracking-wider"
                        >Couture Service</label
                      >
                      <div class="relative">
                        <select
                          class="w-full h-12 px-4 rounded-lg bg-surface-container border border-outline-variant/40 font-body-sm text-body-sm text-on-surface focus:outline-none focus:border-primary appearance-none pr-10 transition-colors duration-300 hover:border-primary/60 cursor-pointer"
                        >
                          <option>Bohemian Knotless Braids (From $320)</option>
                          <option>
                            Sleek Architectural Cornrows (From $190)
                          </option>
                          <option>Precision Stitch Braids (From $220)</option>
                          <option>
                            Luxury Full Lace Wig Install (From $450)
                          </option>
                          <option>
                            Botanical Silk Press &amp; Curls (From $180)
                          </option>
                          <option>
                            Deep Follicle Scalp Therapy (From $160)
                          </option></select
                        ><span
                          class="material-symbols-outlined absolute right-3 top-3 text-on-surface-variant pointer-events-none text-[20px]"
                          >expand_more</span
                        >
                      </div>
                    </div>
                    <div class="flex flex-col gap-2">
                      <label
                        class="font-label-caps text-label-caps text-on-surface uppercase tracking-wider"
                        >Preferred Artisan</label
                      >
                      <div class="relative">
                        <select
                          class="w-full h-12 px-4 rounded-lg bg-surface-container border border-outline-variant/40 font-body-sm text-body-sm text-on-surface focus:outline-none focus:border-primary appearance-none pr-10 transition-colors duration-300 hover:border-primary/60 cursor-pointer"
                        >
                          <option>Simone Laurent (Master Stylist)</option>
                          <option>Chantal Moreau (Senior Braider)</option>
                          <option>
                            First Available Senior Artisan
                          </option></select
                        ><span
                          class="material-symbols-outlined absolute right-3 top-3 text-on-surface-variant pointer-events-none text-[20px]"
                          >expand_more</span
                        >
                      </div>
                    </div>
                    <div class="flex flex-col gap-2">
                      <label
                        class="font-label-caps text-label-caps text-on-surface uppercase tracking-wider"
                        >Preferred Date</label
                      ><input
                        class="w-full h-12 px-4 rounded-lg bg-surface-container border border-outline-variant/40 font-body-sm text-body-sm text-on-surface focus:outline-none focus:border-primary transition-colors duration-300 hover:border-primary/60 cursor-pointer"
                        type="date"
                        value="2025-04-15"
                      />
                    </div>
                    <div class="flex flex-col gap-2">
                      <label
                        class="font-label-caps text-label-caps text-on-surface uppercase tracking-wider"
                        >Time Slot</label
                      >
                      <div class="relative">
                        <select
                          class="w-full h-12 px-4 rounded-lg bg-surface-container border border-outline-variant/40 font-body-sm text-body-sm text-on-surface focus:outline-none focus:border-primary appearance-none pr-10 transition-colors duration-300 hover:border-primary/60 cursor-pointer"
                        >
                          <option>Morning Suite (09:30 AM)</option>
                          <option>Afternoon Suite (01:30 PM)</option>
                          <option>Evening VIP Suite (05:00 PM)</option></select
                        ><span
                          class="material-symbols-outlined absolute right-3 top-3 text-on-surface-variant pointer-events-none text-[20px]"
                          >expand_more</span
                        >
                      </div>
                    </div>
                    <div class="flex flex-col gap-2">
                      <label
                        class="font-label-caps text-label-caps text-on-surface uppercase tracking-wider"
                        >Patron Full Name</label
                      ><input
                        class="w-full h-12 px-4 rounded-lg bg-surface-container border border-outline-variant/40 font-body-sm text-body-sm text-on-surface focus:outline-none focus:border-primary transition-colors duration-300 hover:border-primary/60"
                        placeholder="e.g. Adrienne Dubois"
                        required=""
                        type="text"
                      />
                    </div>
                    <div class="flex flex-col gap-2">
                      <label
                        class="font-label-caps text-label-caps text-on-surface uppercase tracking-wider"
                        >WhatsApp / Mobile</label
                      ><input
                        class="w-full h-12 px-4 rounded-lg bg-surface-container border border-outline-variant/40 font-body-sm text-body-sm text-on-surface focus:outline-none focus:border-primary transition-colors duration-300 hover:border-primary/60"
                        placeholder="+44 7911 123456"
                        required=""
                        type="tel"
                      />
                    </div>
                    <div class="sm:col-span-2 pt-3">
                      <button
                        class="w-full py-4 rounded-full bg-primary text-on-primary font-label-caps text-label-caps uppercase transition-all duration-300 hover:bg-inverse-surface hover:shadow-2xl hover:scale-105 active:scale-95 shadow-xl flex items-center justify-center gap-2 cursor-pointer"
                        type="submit"
                      >
                        <span>Confirm Suite Reservation</span
                        ><span class="material-symbols-outlined text-[18px]"
                          >calendar_today</span
                        >
                      </button>
                    </div>
                  </form>
                  <p
                    class="font-body-sm text-body-sm text-on-surface-variant text-center mt-4"
                  >
                    A 25% deposit secures your private room. Cancellations
                    welcomed with 48h notice.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </section>