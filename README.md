# MaterialDesignIconsEnum
Creates enums and resources C# classes to be able to use the Material Design Icons set (currently version 2.0.46, available here: https://materialdesignicons.com/) in .NET a WPF applications.

The generated MaterialDesignIconsEnum.cs file looks like this:

namespace MaterialDesignIcons
{
	/// <summary>
	/// Material Design Icons Resources.
	/// </summary>
	public enum MaterialDesignIconsEnum
	{
		/// <summary>
		/// access-point glyph (F002).
		/// </summary>
		AccessPoint = 0xF002,

		/// <summary>
		/// access-point-network glyph (F003).
		/// </summary>
		AccessPointNetwork = 0xF003,

		/// <summary>
		/// account glyph (F004).
		/// </summary>
		Account = 0xF004,

		/// <summary>
		/// account-alert glyph (F005).
		/// </summary>
		AccountAlert = 0xF005,
        
        .... etc ...
        
        }
        
	/// <summary>
	/// Material Design Icons Resources.
	/// </summary>
	public static partial class MaterialDesignIconsResource
	{
		/// <summary>
		/// access-point glyph (F002).
		/// </summary>
		public const char AccessPoint = '\uF002';

		/// <summary>
		/// access-point-network glyph (F003).
		/// </summary>
		public const char AccessPointNetwork = '\uF003';

		/// <summary>
		/// account glyph (F004).
		/// </summary>
		public const char Account = '\uF004';

		/// <summary>
		/// account-alert glyph (F005).
		/// </summary>
		public const char AccountAlert = '\uF005';
          
        .... etc ...
        
        }
    }