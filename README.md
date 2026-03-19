# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 18:02:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 2668.3 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84913
telemt_connections_bad_total 2491
telemt_connections_current 1656
telemt_connections_me_current 1656
telemt_handshake_timeouts_total 814
telemt_upstream_connect_attempt_total 378
telemt_upstream_connect_success_total 372
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 219
telemt_me_reconnect_success_total 218
telemt_me_reader_eof_total 210
telemt_me_idle_close_by_peer_total 210
telemt_me_route_drop_no_conn_total 29211
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74320
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 354
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 229
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 74447
telemt_user_connections_current{user="hello"} 1656
telemt_user_octets_from_client{user="hello"} 1275394600 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 26193846128 (24.39 GB)
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 19124.0 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1918386
telemt_connections_bad_total 94864
telemt_connections_current 4261
telemt_connections_me_current 4261
telemt_handshake_timeouts_total 35967
telemt_upstream_connect_attempt_total 4492
telemt_upstream_connect_success_total 4438
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6426
telemt_me_reconnect_success_total 2202
telemt_me_reader_eof_total 2382
telemt_me_idle_close_by_peer_total 2382
telemt_me_route_drop_no_conn_total 1113659
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1590226
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6309
telemt_desync_full_logged_total 1983
telemt_desync_suppressed_total 4326
telemt_desync_frames_bucket_total{bucket="1_2"} 1218
telemt_desync_frames_bucket_total{bucket="3_10"} 2511
telemt_desync_frames_bucket_total{bucket="gt_10"} 2580
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2346
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2147
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 1590218
telemt_user_connections_current{user="hello"} 4261
telemt_user_octets_from_client{user="hello"} 23381390058 (21.78 GB)
telemt_user_octets_to_client{user="hello"} 510351595670 (475.30 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1377
telemt_user_unique_ips_recent_window{user="hello"} 559
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 19090.3 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1624406
telemt_connections_bad_total 59147
telemt_connections_current 2828
telemt_connections_me_current 2828
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 22722
telemt_upstream_connect_attempt_total 25039
telemt_upstream_connect_success_total 23863
telemt_upstream_connect_fail_total 1176
telemt_upstream_connect_attempts_per_request{bucket="1"} 25039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3899
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1176
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4800
telemt_me_reconnect_success_total 2430
telemt_me_reader_eof_total 2508
telemt_me_idle_close_by_peer_total 2507
telemt_me_route_drop_no_conn_total 1404746
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1397842
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5569
telemt_desync_full_logged_total 1757
telemt_desync_suppressed_total 3812
telemt_desync_frames_bucket_total{bucket="1_2"} 1473
telemt_desync_frames_bucket_total{bucket="3_10"} 2048
telemt_desync_frames_bucket_total{bucket="gt_10"} 2048
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 2835
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2426
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 405
telemt_user_connections_total{user="hello"} 1417198
telemt_user_connections_current{user="hello"} 2828
telemt_user_octets_from_client{user="hello"} 25893832813 (24.12 GB)
telemt_user_octets_to_client{user="hello"} 308421125605 (287.24 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 928
telemt_user_unique_ips_recent_window{user="hello"} 434
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 72813.2 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5256026
telemt_connections_bad_total 920214
telemt_connections_current 3395
telemt_connections_me_current 3395
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 97798
telemt_upstream_connect_attempt_total 64642
telemt_upstream_connect_success_total 62151
telemt_upstream_connect_fail_total 2491
telemt_upstream_connect_attempts_per_request{bucket="1"} 64642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1041
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74743
telemt_me_reconnect_success_total 9337
telemt_me_reader_eof_total 9837
telemt_me_idle_close_by_peer_total 9834
telemt_me_route_drop_no_conn_total 2457505
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3682863
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16038
telemt_desync_full_logged_total 4892
telemt_desync_suppressed_total 11146
telemt_desync_frames_bucket_total{bucket="1_2"} 2631
telemt_desync_frames_bucket_total{bucket="3_10"} 6703
telemt_desync_frames_bucket_total{bucket="gt_10"} 6704
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 9577
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9313
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 3730983
telemt_user_connections_current{user="hello"} 3395
telemt_user_octets_from_client{user="hello"} 58071990523 (54.08 GB)
telemt_user_octets_to_client{user="hello"} 1366896828968 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1166
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 19054.4 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453150
telemt_connections_bad_total 29536
telemt_connections_current 696
telemt_connections_me_current 696
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 9494
telemt_upstream_connect_attempt_total 6812
telemt_upstream_connect_success_total 6616
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 6812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 539
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 410
telemt_me_reconnect_attempts_total 2674
telemt_me_reconnect_success_total 2622
telemt_me_reader_eof_total 2679
telemt_me_idle_close_by_peer_total 2678
telemt_me_route_drop_no_conn_total 313367
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358376
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 997
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 686
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 403
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 12
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 101
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2623
telemt_me_writer_restored_same_endpoint_total 2613
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 376590
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 4538116260 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 82066715290 (76.43 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 19054.4 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1269902
telemt_connections_bad_total 84309
telemt_connections_current 3237
telemt_connections_me_current 3237
telemt_handshake_timeouts_total 22694
telemt_upstream_connect_attempt_total 3197
telemt_upstream_connect_success_total 3173
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 3197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 2184
telemt_me_reconnect_success_total 2159
telemt_me_reader_eof_total 2259
telemt_me_idle_close_by_peer_total 2259
telemt_me_route_drop_no_conn_total 491629
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1092064
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5950
telemt_desync_full_logged_total 1804
telemt_desync_suppressed_total 4146
telemt_desync_frames_bucket_total{bucket="1_2"} 1175
telemt_desync_frames_bucket_total{bucket="3_10"} 2060
telemt_desync_frames_bucket_total{bucket="gt_10"} 2715
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 2202
telemt_me_writer_restored_same_endpoint_total 2142
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 1091571
telemt_user_connections_current{user="hello"} 3237
telemt_user_octets_from_client{user="hello"} 16904272624 (15.74 GB)
telemt_user_octets_to_client{user="hello"} 477551809000 (444.75 GB)
telemt_user_unique_ips_current{user="hello"} 1037
telemt_user_unique_ips_recent_window{user="hello"} 414
```