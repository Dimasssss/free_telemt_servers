# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-14 08:24:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 175850.9 (48h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 676556
telemt_connections_bad_total 32486
telemt_handshake_timeouts_total 13245
telemt_upstream_connect_attempt_total 44708
telemt_upstream_connect_success_total 44480
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 44708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5746
telemt_me_reconnect_attempts_total 40028
telemt_me_reconnect_success_total 35333
telemt_me_reader_eof_total 37780
telemt_me_idle_close_by_peer_total 37779
telemt_me_route_drop_no_conn_total 223834
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 577244
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2235
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1477
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 819
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 35858
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35313
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 577136
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 16789695646 (15.64 GB)
telemt_user_octets_to_client{user="hello"} 276700389356 (257.70 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 175744.6 (48h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340439
telemt_connections_bad_total 2329
telemt_handshake_timeouts_total 3001
telemt_upstream_connect_attempt_total 151974
telemt_upstream_connect_success_total 150668
telemt_upstream_connect_fail_total 1306
telemt_upstream_connect_attempts_per_request{bucket="1"} 151974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1306
telemt_me_keepalive_timeout_total 5312
telemt_me_reconnect_attempts_total 179196
telemt_me_reconnect_success_total 38591
telemt_me_reader_eof_total 44035
telemt_me_idle_close_by_peer_total 44035
telemt_me_route_drop_no_conn_total 114552
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218598
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 43361
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 38574
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4770
telemt_user_connections_total{user="hello"} 321704
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 3321754259 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 104437951463 (97.27 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 175708.5 (48h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 397930
telemt_connections_bad_total 3193
telemt_handshake_timeouts_total 35357
telemt_upstream_connect_attempt_total 46376
telemt_upstream_connect_success_total 46367
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 46376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3507
telemt_me_reconnect_attempts_total 38850
telemt_me_reconnect_success_total 37559
telemt_me_reader_eof_total 40381
telemt_me_idle_close_by_peer_total 40381
telemt_me_route_drop_no_conn_total 143827
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345390
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 38014
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37538
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 345151
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 13649952400 (12.71 GB)
telemt_user_octets_to_client{user="hello"} 143626722724 (133.76 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 175684.0 (48h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500358
telemt_connections_bad_total 16280
telemt_handshake_timeouts_total 4577
telemt_upstream_connect_attempt_total 76885
telemt_upstream_connect_success_total 66259
telemt_upstream_connect_fail_total 10626
telemt_upstream_connect_attempts_per_request{bucket="1"} 76885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10626
telemt_me_keepalive_timeout_total 5480
telemt_me_reconnect_attempts_total 147630
telemt_me_reconnect_success_total 38463
telemt_me_reader_eof_total 43103
telemt_me_idle_close_by_peer_total 43095
telemt_me_route_drop_no_conn_total 181143
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 427093
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1851
telemt_desync_full_logged_total 551
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 437
telemt_desync_frames_bucket_total{bucket="3_10"} 708
telemt_desync_frames_bucket_total{bucket="gt_10"} 706
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 42312
telemt_me_refill_failed_total 3404
telemt_me_writer_restored_same_endpoint_total 38453
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3849
telemt_user_connections_total{user="hello"} 445968
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 9613888239 (8.95 GB)
telemt_user_octets_to_client{user="hello"} 183326472940 (170.74 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 125855.5 (34h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206257
telemt_connections_bad_total 31248
telemt_handshake_timeouts_total 1766
telemt_upstream_connect_attempt_total 44273
telemt_upstream_connect_success_total 43848
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 44273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 2562
telemt_me_reconnect_attempts_total 46148
telemt_me_reconnect_success_total 32711
telemt_me_reader_eof_total 34977
telemt_me_idle_close_by_peer_total 34977
telemt_me_route_drop_no_conn_total 61862
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162710
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 33430
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 32693
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 167470
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 2465311113 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 79984049287 (74.49 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 175640.2 (48h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1009808
telemt_connections_bad_total 36311
telemt_handshake_timeouts_total 26279
telemt_upstream_connect_attempt_total 36496
telemt_upstream_connect_success_total 36301
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 36496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 4754
telemt_me_reconnect_attempts_total 32279
telemt_me_reconnect_success_total 27597
telemt_me_reader_eof_total 29606
telemt_me_idle_close_by_peer_total 29603
telemt_me_route_drop_no_conn_total 474322
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 935919
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 783
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 28092
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27590
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 908550
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 15435621876 (14.38 GB)
telemt_user_octets_to_client{user="hello"} 452256218752 (421.20 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 73
```