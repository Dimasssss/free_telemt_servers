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

# Server Metrics 2026-03-19 04:21:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 23564.4 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324100
telemt_connections_bad_total 34829
telemt_connections_current 900
telemt_connections_me_current 900
telemt_handshake_timeouts_total 19160
telemt_upstream_connect_attempt_total 4636
telemt_upstream_connect_success_total 4563
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 4636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3380
telemt_me_reconnect_success_total 3364
telemt_me_reader_eof_total 3542
telemt_me_idle_close_by_peer_total 3542
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 81916
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235265
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1678
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3391
telemt_me_writer_restored_same_endpoint_total 3347
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 232512
telemt_user_connections_current{user="hello"} 900
telemt_user_octets_from_client{user="hello"} 2587489404 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 69688173012 (64.90 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 23568.1 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588104
telemt_connections_bad_total 38953
telemt_connections_current 2373
telemt_connections_me_current 2373
telemt_handshake_timeouts_total 16140
telemt_upstream_connect_attempt_total 4453
telemt_upstream_connect_success_total 4371
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 4453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_reconnect_attempts_total 3178
telemt_me_reconnect_success_total 3162
telemt_me_reader_eof_total 3333
telemt_me_idle_close_by_peer_total 3333
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 175893
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 484093
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1869
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 372
telemt_desync_frames_bucket_total{bucket="3_10"} 683
telemt_desync_frames_bucket_total{bucket="gt_10"} 814
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3214
telemt_me_writer_restored_same_endpoint_total 3144
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 484041
telemt_user_connections_current{user="hello"} 2373
telemt_user_octets_from_client{user="hello"} 14222213916 (13.25 GB)
telemt_user_octets_to_client{user="hello"} 212408812484 (197.82 GB)
telemt_user_unique_ips_current{user="hello"} 892
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 23565.3 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491105
telemt_connections_bad_total 102683
telemt_connections_current 1876
telemt_connections_me_current 1876
telemt_handshake_timeouts_total 14829
telemt_upstream_connect_attempt_total 4384
telemt_upstream_connect_success_total 4383
telemt_upstream_connect_attempts_per_request{bucket="1"} 4383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 3188
telemt_me_reconnect_success_total 3177
telemt_me_reader_eof_total 3361
telemt_me_idle_close_by_peer_total 3361
telemt_me_route_drop_no_conn_total 145983
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353341
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1699
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1069
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 715
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3229
telemt_me_writer_restored_same_endpoint_total 3161
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 353336
telemt_user_connections_current{user="hello"} 1876
telemt_user_octets_from_client{user="hello"} 7681049452 (7.15 GB)
telemt_user_octets_to_client{user="hello"} 221089177400 (205.91 GB)
telemt_user_unique_ips_current{user="hello"} 728
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 23618.6 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586943
telemt_connections_bad_total 71078
telemt_connections_current 1642
telemt_connections_me_current 1642
telemt_handshake_timeouts_total 11703
telemt_upstream_connect_attempt_total 4271
telemt_upstream_connect_success_total 4271
telemt_upstream_connect_attempts_per_request{bucket="1"} 4271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 3080
telemt_me_reconnect_success_total 3069
telemt_me_reader_eof_total 3236
telemt_me_idle_close_by_peer_total 3235
telemt_me_route_drop_no_conn_total 146119
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353144
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1021
telemt_desync_full_logged_total 373
telemt_desync_suppressed_total 648
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 376
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3103
telemt_me_writer_restored_same_endpoint_total 3045
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 352900
telemt_user_connections_current{user="hello"} 1642
telemt_user_octets_from_client{user="hello"} 4268849156 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 135413988408 (126.11 GB)
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 23562.0 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654203
telemt_connections_bad_total 181732
telemt_connections_current 1893
telemt_connections_me_current 1893
telemt_handshake_timeouts_total 19043
telemt_upstream_connect_attempt_total 4382
telemt_upstream_connect_success_total 4354
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 3162
telemt_me_reconnect_success_total 3144
telemt_me_reader_eof_total 3322
telemt_me_idle_close_by_peer_total 3322
telemt_me_route_drop_no_conn_total 160762
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383287
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1670
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1022
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 577
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3173
telemt_me_writer_restored_same_endpoint_total 3120
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 383204
telemt_user_connections_current{user="hello"} 1893
telemt_user_octets_from_client{user="hello"} 11344427972 (10.57 GB)
telemt_user_octets_to_client{user="hello"} 223884501712 (208.51 GB)
telemt_user_unique_ips_current{user="hello"} 740
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 23573.4 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115527
telemt_connections_bad_total 10225
telemt_connections_current 461
telemt_connections_me_current 461
telemt_handshake_timeouts_total 529
telemt_upstream_connect_attempt_total 6514
telemt_upstream_connect_success_total 6332
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 6514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_reconnect_attempts_total 6970
telemt_me_reconnect_success_total 5130
telemt_me_reader_eof_total 5386
telemt_me_idle_close_by_peer_total 5386
telemt_me_route_drop_no_conn_total 47957
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100945
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5200
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5100
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 100935
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 1897092976 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 64919154148 (60.46 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 23564.4 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371783
telemt_connections_bad_total 39223
telemt_connections_current 1691
telemt_connections_me_current 1691
telemt_handshake_timeouts_total 19458
telemt_upstream_connect_attempt_total 4950
telemt_upstream_connect_success_total 4950
telemt_upstream_connect_attempts_per_request{bucket="1"} 4950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3758
telemt_me_reconnect_success_total 3748
telemt_me_reader_eof_total 3954
telemt_me_idle_close_by_peer_total 3954
telemt_me_route_drop_no_conn_total 105377
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301597
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1546
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 960
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 603
telemt_desync_frames_bucket_total{bucket="gt_10"} 632
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3788
telemt_me_writer_restored_same_endpoint_total 3733
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 301617
telemt_user_connections_current{user="hello"} 1691
telemt_user_octets_from_client{user="hello"} 3511640140 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 170602875576 (158.89 GB)
telemt_user_unique_ips_current{user="hello"} 627
telemt_user_unique_ips_recent_window{user="hello"} 210
```