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

# Server Metrics 2026-03-17 01:24:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 23926.4 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133830
telemt_connections_bad_total 2083
telemt_handshake_timeouts_total 5119
telemt_upstream_connect_attempt_total 5025
telemt_upstream_connect_success_total 4995
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 5025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3802
telemt_me_reconnect_success_total 3788
telemt_me_reader_eof_total 4024
telemt_me_idle_close_by_peer_total 4024
telemt_me_route_drop_no_conn_total 40683
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120957
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3816
telemt_me_writer_restored_same_endpoint_total 3767
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 120884
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 1726658792 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 56778965008 (52.88 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 24177.5 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77924
telemt_connections_bad_total 972
telemt_handshake_timeouts_total 2903
telemt_upstream_connect_attempt_total 5901
telemt_upstream_connect_success_total 5824
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 5901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_reconnect_attempts_total 4638
telemt_me_reconnect_success_total 4626
telemt_me_reader_eof_total 4881
telemt_me_idle_close_by_peer_total 4881
telemt_me_route_drop_no_conn_total 31531
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70858
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4678
telemt_me_writer_restored_same_endpoint_total 4610
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 70801
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1086039140 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 34149691888 (31.80 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 23953.8 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49404
telemt_connections_bad_total 495
telemt_handshake_timeouts_total 1812
telemt_upstream_connect_attempt_total 6502
telemt_upstream_connect_success_total 6462
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 6502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 5275
telemt_me_reconnect_success_total 5245
telemt_me_reader_eof_total 5603
telemt_me_idle_close_by_peer_total 5603
telemt_me_route_drop_no_conn_total 15201
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41477
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5306
telemt_me_writer_restored_same_endpoint_total 5234
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 41462
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 3799332892 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 15061428076 (14.03 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 24013.2 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77426
telemt_connections_bad_total 3054
telemt_handshake_timeouts_total 475
telemt_upstream_connect_attempt_total 5526
telemt_upstream_connect_success_total 5475
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 5526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 4291
telemt_me_reconnect_success_total 4262
telemt_me_reader_eof_total 4514
telemt_me_idle_close_by_peer_total 4514
telemt_me_route_drop_no_conn_total 26325
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71793
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 145
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4316
telemt_me_writer_restored_same_endpoint_total 4255
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 71777
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 874441076 (833.93 MB)
telemt_user_octets_to_client{user="hello"} 31070890980 (28.94 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 23985.1 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57660
telemt_connections_bad_total 14936
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 6808
telemt_upstream_connect_success_total 6714
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 6808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 6626
telemt_me_reconnect_success_total 5504
telemt_me_reader_eof_total 5774
telemt_me_idle_close_by_peer_total 5774
telemt_me_route_drop_no_conn_total 16292
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40722
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 5637
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 5496
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 40717
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 311711240 (297.27 MB)
telemt_user_octets_to_client{user="hello"} 13697230680 (12.76 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 24146.0 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143351
telemt_connections_bad_total 4521
telemt_handshake_timeouts_total 999
telemt_upstream_connect_attempt_total 4943
telemt_upstream_connect_success_total 4915
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 3725
telemt_me_reconnect_success_total 3713
telemt_me_reader_eof_total 3967
telemt_me_idle_close_by_peer_total 3967
telemt_me_route_drop_no_conn_total 168383
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210618
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 128
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3763
telemt_me_writer_restored_same_endpoint_total 3703
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 132866
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 2243591872 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 111488237412 (103.83 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 12152.5 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 5786
telemt_upstream_connect_success_total 5785
telemt_upstream_connect_attempts_per_request{bucket="1"} 5785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 5157
telemt_me_reconnect_success_total 5126
telemt_me_reader_eof_total 5638
telemt_me_idle_close_by_peer_total 5638
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5175
telemt_me_writer_restored_same_endpoint_total 5126
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```