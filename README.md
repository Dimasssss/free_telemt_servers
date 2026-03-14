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

# Server Metrics 2026-03-14 07:02:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 170961.4 (47h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 655786
telemt_connections_bad_total 32373
telemt_handshake_timeouts_total 13054
telemt_upstream_connect_attempt_total 43453
telemt_upstream_connect_success_total 43234
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 43453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5679
telemt_me_reconnect_attempts_total 39043
telemt_me_reconnect_success_total 34352
telemt_me_reader_eof_total 36735
telemt_me_idle_close_by_peer_total 36734
telemt_me_route_drop_no_conn_total 216186
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557563
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2070
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1362
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 757
telemt_desync_frames_bucket_total{bucket="gt_10"} 863
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 34868
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34332
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 557447
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 16322726934 (15.20 GB)
telemt_user_octets_to_client{user="hello"} 268786613660 (250.33 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 170854.0 (47h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330648
telemt_connections_bad_total 2324
telemt_handshake_timeouts_total 2518
telemt_upstream_connect_attempt_total 150260
telemt_upstream_connect_success_total 148995
telemt_upstream_connect_fail_total 1265
telemt_upstream_connect_attempts_per_request{bucket="1"} 150260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1265
telemt_me_keepalive_timeout_total 4003
telemt_me_reconnect_attempts_total 177780
telemt_me_reconnect_success_total 37189
telemt_me_reader_eof_total 42563
telemt_me_idle_close_by_peer_total 42563
telemt_me_route_drop_no_conn_total 108332
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209950
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
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 41930
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 37172
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4741
telemt_user_connections_total{user="hello"} 313058
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 3258833971 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 102201690575 (95.18 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 170818.0 (47h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385977
telemt_connections_bad_total 2970
telemt_handshake_timeouts_total 35096
telemt_upstream_connect_attempt_total 45044
telemt_upstream_connect_success_total 45035
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24386
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3473
telemt_me_reconnect_attempts_total 37782
telemt_me_reconnect_success_total 36496
telemt_me_reader_eof_total 39246
telemt_me_idle_close_by_peer_total 39246
telemt_me_route_drop_no_conn_total 139368
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334483
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 36936
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36475
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 334254
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 13501249472 (12.57 GB)
telemt_user_octets_to_client{user="hello"} 131646842580 (122.61 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 170793.3 (47h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488183
telemt_connections_bad_total 16239
telemt_handshake_timeouts_total 4525
telemt_upstream_connect_attempt_total 75469
telemt_upstream_connect_success_total 64890
telemt_upstream_connect_fail_total 10579
telemt_upstream_connect_attempts_per_request{bucket="1"} 75469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 342
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10579
telemt_me_keepalive_timeout_total 5402
telemt_me_reconnect_attempts_total 143421
telemt_me_reconnect_success_total 37360
telemt_me_reader_eof_total 41873
telemt_me_idle_close_by_peer_total 41865
telemt_me_route_drop_no_conn_total 176155
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415414
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1774
telemt_desync_full_logged_total 529
telemt_desync_suppressed_total 1245
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 41100
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37350
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3740
telemt_user_connections_total{user="hello"} 434260
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 9365529863 (8.72 GB)
telemt_user_octets_to_client{user="hello"} 177834004692 (165.62 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 120964.8 (33h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197311
telemt_connections_bad_total 29219
telemt_handshake_timeouts_total 1731
telemt_upstream_connect_attempt_total 42742
telemt_upstream_connect_success_total 42336
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 42742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_keepalive_timeout_total 2501
telemt_me_reconnect_attempts_total 44854
telemt_me_reconnect_success_total 31424
telemt_me_reader_eof_total 33643
telemt_me_idle_close_by_peer_total 33643
telemt_me_route_drop_no_conn_total 58677
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156109
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 646
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 32132
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31406
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 708
telemt_user_connections_total{user="hello"} 160857
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 2392961401 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 74454453903 (69.34 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 170749.3 (47h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 975689
telemt_connections_bad_total 36056
telemt_handshake_timeouts_total 26065
telemt_upstream_connect_attempt_total 35436
telemt_upstream_connect_success_total 35248
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 35436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 4720
telemt_me_reconnect_attempts_total 31489
telemt_me_reconnect_success_total 26810
telemt_me_reader_eof_total 28781
telemt_me_idle_close_by_peer_total 28778
telemt_me_route_drop_no_conn_total 460194
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904986
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 27296
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26803
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 877633
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 15072761576 (14.04 GB)
telemt_user_octets_to_client{user="hello"} 443880962944 (413.40 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 65
```