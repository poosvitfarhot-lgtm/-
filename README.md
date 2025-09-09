@@ -162,11 +162,11 @@ export interface SkinViewerOptions {
	 * @defaultValue If unspecified, the ears will be invisible.
	 */
	ears?:
	| "current-skin"
	| {
		textureType: "standalone" | "skin";
		source: RemoteImage | TextureSource;
	};
		| "current-skin"
		| {
				textureType: "standalone" | "skin";
				source: RemoteImage | TextureSource;
		  };

	/**
	 * Whether to preserve the buffers until manually cleared or overwritten.
