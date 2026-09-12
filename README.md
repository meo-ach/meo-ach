import { InfiniteSlider } from '@/components/core/infinite-slider';

export function NameSlider() {
  return (
    <div className="w-full overflow-hidden py-6">
      <InfiniteSlider speed={40} speedOnHover={15} gap={50}>
        <span className="whitespace-nowrap text-5xl font-bold tracking-wide text-pink-400">
          NIDHI NAIK 🎀
        </span>

        <span className="whitespace-nowrap text-5xl font-bold tracking-wide text-purple-400">
          NIDHI NAIK ✿
        </span>

        <span className="whitespace-nowrap text-5xl font-bold tracking-wide text-pink-400">
          NIDHI NAIK ♡
        </span>

        <span className="whitespace-nowrap text-5xl font-bold tracking-wide text-purple-400">
          NIDHI NAIK ✦
        </span>

        <span className="whitespace-nowrap text-5xl font-bold tracking-wide text-pink-400">
          NIDHI NAIK 🎀
        </span>

        <span className="whitespace-nowrap text-5xl font-bold tracking-wide text-purple-400">
          NIDHI NAIK ✿
        </span>
      </InfiniteSlider>
    </div>
  );
}
