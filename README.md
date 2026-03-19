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

# Server Metrics 2026-03-19 13:23:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 2499.7 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109573
telemt_connections_bad_total 4367
telemt_connections_current 1592
telemt_connections_me_current 1592
telemt_handshake_timeouts_total 2177
telemt_upstream_connect_attempt_total 344
telemt_upstream_connect_success_total 323
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 181
telemt_me_reconnect_success_total 165
telemt_me_reader_eof_total 159
telemt_me_idle_close_by_peer_total 159
telemt_me_route_drop_no_conn_total 88659
telemt_me_route_drop_channel_closed_total 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97214
telemt_me_writer_pick_total{mode="p2c",result="full"} 54
telemt_me_writer_pick_total{mode="p2c",result="closed"} 152
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 406
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 179
telemt_me_writer_restored_same_endpoint_total 154
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 220
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 96801
telemt_user_connections_current{user="hello"} 1592
telemt_user_octets_from_client{user="hello"} 1407843284 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 27257229112 (25.39 GB)
telemt_user_unique_ips_current{user="hello"} 576
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 2409.6 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291923
telemt_connections_bad_total 7381
telemt_connections_current 3821
telemt_connections_me_current 3821
telemt_handshake_timeouts_total 3088
telemt_upstream_connect_attempt_total 1894
telemt_upstream_connect_success_total 1883
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 929
telemt_me_reconnect_success_total 506
telemt_me_reader_eof_total 467
telemt_me_idle_close_by_peer_total 467
telemt_me_route_drop_no_conn_total 283701
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261117
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 559
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 492
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 451
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_user_connections_total{user="hello"} 261964
telemt_user_connections_current{user="hello"} 3821
telemt_user_octets_from_client{user="hello"} 4285363594 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 60874218178 (56.69 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1343
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 2375.1 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230475
telemt_connections_bad_total 29628
telemt_connections_current 2948
telemt_connections_me_current 2948
telemt_handshake_timeouts_total 2584
telemt_upstream_connect_attempt_total 432
telemt_upstream_connect_success_total 418
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 271
telemt_me_reconnect_success_total 263
telemt_me_reader_eof_total 224
telemt_me_idle_close_by_peer_total 224
telemt_me_route_drop_no_conn_total 136695
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181770
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 586
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 245
telemt_me_writer_restored_same_endpoint_total 260
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 181590
telemt_user_connections_current{user="hello"} 2948
telemt_user_octets_from_client{user="hello"} 1981519524 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 39529295788 (36.81 GB)
telemt_user_unique_ips_current{user="hello"} 980
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 56098.5 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3782137
telemt_connections_bad_total 744192
telemt_connections_current 3681
telemt_connections_me_current 3681
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 75033
telemt_upstream_connect_attempt_total 61795
telemt_upstream_connect_success_total 59312
telemt_upstream_connect_fail_total 2482
telemt_upstream_connect_attempts_per_request{bucket="1"} 61794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1014
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2482
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70369
telemt_me_reconnect_success_total 7314
telemt_me_reader_eof_total 7647
telemt_me_idle_close_by_peer_total 7644
telemt_me_route_drop_no_conn_total 1677024
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2546702
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
telemt_desync_total 11063
telemt_desync_full_logged_total 3411
telemt_desync_suppressed_total 7652
telemt_desync_frames_bucket_total{bucket="1_2"} 1962
telemt_desync_frames_bucket_total{bucket="3_10"} 4737
telemt_desync_frames_bucket_total{bucket="gt_10"} 4364
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7439
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7290
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 2595462
telemt_user_connections_current{user="hello"} 3681
telemt_user_octets_from_client{user="hello"} 41207820451 (38.38 GB)
telemt_user_octets_to_client{user="hello"} 944219345768 (879.37 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1168
telemt_user_unique_ips_recent_window{user="hello"} 559
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 2339.2 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62118
telemt_connections_bad_total 1783
telemt_connections_current 856
telemt_connections_me_current 856
telemt_handshake_timeouts_total 3533
telemt_upstream_connect_attempt_total 394
telemt_upstream_connect_success_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_reconnect_attempts_total 240
telemt_me_reconnect_success_total 234
telemt_me_reader_eof_total 178
telemt_me_idle_close_by_peer_total 178
telemt_me_route_drop_no_conn_total 56412
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54041
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
telemt_desync_total 96
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 198
telemt_me_writer_restored_same_endpoint_total 225
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 145
telemt_me_async_recovery_trigger_total 933
telemt_user_connections_total{user="hello"} 54600
telemt_user_connections_current{user="hello"} 856
telemt_user_octets_from_client{user="hello"} 830604544 (792.13 MB)
telemt_user_octets_to_client{user="hello"} 10689081396 (9.95 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 2339.7 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165711
telemt_connections_bad_total 12004
telemt_connections_current 3246
telemt_connections_me_current 3246
telemt_handshake_timeouts_total 2545
telemt_upstream_connect_attempt_total 368
telemt_upstream_connect_success_total 365
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 213
telemt_me_reconnect_success_total 208
telemt_me_reader_eof_total 196
telemt_me_idle_close_by_peer_total 196
telemt_me_route_drop_no_conn_total 50599
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145279
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 676
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 212
telemt_me_writer_restored_same_endpoint_total 191
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 145259
telemt_user_connections_current{user="hello"} 3246
telemt_user_octets_from_client{user="hello"} 1717956860 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 60532464808 (56.38 GB)
telemt_user_unique_ips_current{user="hello"} 1053
telemt_user_unique_ips_recent_window{user="hello"} 449
```