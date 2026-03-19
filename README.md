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

# Server Metrics 2026-03-19 13:28:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 2805.4 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124034
telemt_connections_bad_total 4876
telemt_connections_current 1582
telemt_connections_me_current 1582
telemt_handshake_timeouts_total 2796
telemt_upstream_connect_attempt_total 400
telemt_upstream_connect_success_total 377
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 199
telemt_me_reconnect_success_total 183
telemt_me_reader_eof_total 177
telemt_me_idle_close_by_peer_total 177
telemt_me_route_drop_no_conn_total 109237
telemt_me_route_drop_channel_closed_total 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109740
telemt_me_writer_pick_total{mode="p2c",result="full"} 54
telemt_me_writer_pick_total{mode="p2c",result="closed"} 152
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 442
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_restored_same_endpoint_total 172
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 220
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 109325
telemt_user_connections_current{user="hello"} 1582
telemt_user_octets_from_client{user="hello"} 1463378632 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 29317615348 (27.30 GB)
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 2715.4 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319277
telemt_connections_bad_total 8229
telemt_connections_current 3733
telemt_connections_me_current 3733
telemt_handshake_timeouts_total 3540
telemt_upstream_connect_attempt_total 1942
telemt_upstream_connect_success_total 1931
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 977
telemt_me_reconnect_success_total 554
telemt_me_reader_eof_total 517
telemt_me_idle_close_by_peer_total 517
telemt_me_route_drop_no_conn_total 296620
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285852
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 878
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 604
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 542
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 499
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_user_connections_total{user="hello"} 286718
telemt_user_connections_current{user="hello"} 3733
telemt_user_octets_from_client{user="hello"} 4672989414 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 68925808278 (64.19 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1310
telemt_user_unique_ips_recent_window{user="hello"} 579
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 2693.7 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382897
telemt_connections_bad_total 30501
telemt_connections_current 3105
telemt_connections_me_current 3105
telemt_handshake_timeouts_total 3992
telemt_upstream_connect_attempt_total 409
telemt_upstream_connect_success_total 406
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1146
telemt_me_reconnect_success_total 250
telemt_me_reader_eof_total 173
telemt_me_idle_close_by_peer_total 172
telemt_me_route_drop_no_conn_total 387000
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277731
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 891
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 682
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 197
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 249
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 277345
telemt_user_connections_current{user="hello"} 3105
telemt_user_octets_from_client{user="hello"} 1862558000 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 58283586944 (54.28 GB)
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 2681.3 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253671
telemt_connections_bad_total 32647
telemt_connections_current 3015
telemt_connections_me_current 3015
telemt_handshake_timeouts_total 3102
telemt_upstream_connect_attempt_total 458
telemt_upstream_connect_success_total 443
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 297
telemt_me_reconnect_success_total 288
telemt_me_reader_eof_total 251
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 146819
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199648
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 315
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 272
telemt_me_writer_restored_same_endpoint_total 285
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 199466
telemt_user_connections_current{user="hello"} 3015
telemt_user_octets_from_client{user="hello"} 2158542652 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 45156022432 (42.05 GB)
telemt_user_unique_ips_current{user="hello"} 1017
telemt_user_unique_ips_recent_window{user="hello"} 465
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 56404.3 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3806666
telemt_connections_bad_total 745929
telemt_connections_current 3472
telemt_connections_me_current 3472
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 75758
telemt_upstream_connect_attempt_total 61812
telemt_upstream_connect_success_total 59330
telemt_upstream_connect_fail_total 2482
telemt_upstream_connect_attempts_per_request{bucket="1"} 61812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1014
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2482
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70386
telemt_me_reconnect_success_total 7332
telemt_me_reader_eof_total 7666
telemt_me_idle_close_by_peer_total 7663
telemt_me_route_drop_no_conn_total 1686455
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2567345
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11183
telemt_desync_full_logged_total 3446
telemt_desync_suppressed_total 7737
telemt_desync_frames_bucket_total{bucket="1_2"} 1978
telemt_desync_frames_bucket_total{bucket="3_10"} 4792
telemt_desync_frames_bucket_total{bucket="gt_10"} 4413
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7458
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7308
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 2616099
telemt_user_connections_current{user="hello"} 3472
telemt_user_octets_from_client{user="hello"} 41551399483 (38.70 GB)
telemt_user_octets_to_client{user="hello"} 952349674200 (886.94 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1168
telemt_user_unique_ips_recent_window{user="hello"} 550
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 2646.2 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69974
telemt_connections_bad_total 2725
telemt_connections_current 894
telemt_connections_me_current 894
telemt_handshake_timeouts_total 4461
telemt_upstream_connect_attempt_total 419
telemt_upstream_connect_success_total 419
telemt_upstream_connect_attempts_per_request{bucket="1"} 419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_reconnect_attempts_total 265
telemt_me_reconnect_success_total 259
telemt_me_reader_eof_total 203
telemt_me_idle_close_by_peer_total 203
telemt_me_route_drop_no_conn_total 63992
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59820
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 223
telemt_me_writer_restored_same_endpoint_total 250
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 145
telemt_me_async_recovery_trigger_total 933
telemt_user_connections_total{user="hello"} 60376
telemt_user_connections_current{user="hello"} 894
telemt_user_octets_from_client{user="hello"} 861633372 (821.72 MB)
telemt_user_octets_to_client{user="hello"} 11730203780 (10.92 GB)
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 2645.7 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190498
telemt_connections_bad_total 18151
telemt_connections_current 3239
telemt_connections_me_current 3239
telemt_handshake_timeouts_total 3066
telemt_upstream_connect_attempt_total 382
telemt_upstream_connect_success_total 379
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 227
telemt_me_reconnect_success_total 222
telemt_me_reader_eof_total 212
telemt_me_idle_close_by_peer_total 212
telemt_me_route_drop_no_conn_total 55521
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162933
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 791
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 566
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 228
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 162900
telemt_user_connections_current{user="hello"} 3239
telemt_user_octets_from_client{user="hello"} 1943041776 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 68532501160 (63.83 GB)
telemt_user_unique_ips_current{user="hello"} 1051
telemt_user_unique_ips_recent_window{user="hello"} 446
```