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

# Server Metrics 2026-03-17 02:50:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 29115.3 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153149
telemt_connections_bad_total 2344
telemt_handshake_timeouts_total 5426
telemt_upstream_connect_attempt_total 6290
telemt_upstream_connect_success_total 6252
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 6290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4799
telemt_me_reconnect_success_total 4784
telemt_me_reader_eof_total 5089
telemt_me_idle_close_by_peer_total 5089
telemt_me_route_drop_no_conn_total 47655
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138907
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 781
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 398
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4824
telemt_me_writer_restored_same_endpoint_total 4763
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 138841
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 1888617872 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 62609758924 (58.31 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 29366.6 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86241
telemt_connections_bad_total 1358
telemt_handshake_timeouts_total 2928
telemt_upstream_connect_attempt_total 8009
telemt_upstream_connect_success_total 7903
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 8009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_reconnect_attempts_total 7607
telemt_me_reconnect_success_total 6441
telemt_me_reader_eof_total 6794
telemt_me_idle_close_by_peer_total 6794
telemt_me_route_drop_no_conn_total 36171
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78413
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 185
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6541
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6425
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 78357
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1144656216 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 36762847392 (34.24 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 29142.8 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55628
telemt_connections_bad_total 695
telemt_handshake_timeouts_total 1907
telemt_upstream_connect_attempt_total 7876
telemt_upstream_connect_success_total 7830
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 7876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 6383
telemt_me_reconnect_success_total 6346
telemt_me_reader_eof_total 6785
telemt_me_idle_close_by_peer_total 6785
telemt_me_route_drop_no_conn_total 17546
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46893
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6427
telemt_me_writer_restored_same_endpoint_total 6335
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 46877
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 5561487904 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 17585269928 (16.38 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 29201.9 (8h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87296
telemt_connections_bad_total 3377
telemt_handshake_timeouts_total 1290
telemt_upstream_connect_attempt_total 6808
telemt_upstream_connect_success_total 6748
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 6808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 5304
telemt_me_reconnect_success_total 5267
telemt_me_reader_eof_total 5594
telemt_me_idle_close_by_peer_total 5594
telemt_me_route_drop_no_conn_total 30106
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80200
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 148
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5342
telemt_me_writer_restored_same_endpoint_total 5260
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 80184
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 929696732 (886.63 MB)
telemt_user_octets_to_client{user="hello"} 37402188520 (34.83 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 29173.9 (8h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66371
telemt_connections_bad_total 15908
telemt_handshake_timeouts_total 824
telemt_upstream_connect_attempt_total 8644
telemt_upstream_connect_success_total 8535
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 8644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_reconnect_attempts_total 9307
telemt_me_reconnect_success_total 7059
telemt_me_reader_eof_total 7446
telemt_me_idle_close_by_peer_total 7446
telemt_me_route_drop_no_conn_total 18977
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47743
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 7237
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 7051
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 47737
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 559104160 (533.20 MB)
telemt_user_octets_to_client{user="hello"} 14973018908 (13.94 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 29335.0 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165488
telemt_connections_bad_total 10492
telemt_handshake_timeouts_total 1082
telemt_upstream_connect_attempt_total 6090
telemt_upstream_connect_success_total 6055
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 6090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 4607
telemt_me_reconnect_success_total 4591
telemt_me_reader_eof_total 4924
telemt_me_idle_close_by_peer_total 4924
telemt_me_route_drop_no_conn_total 178250
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226160
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4656
telemt_me_writer_restored_same_endpoint_total 4581
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 148415
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 2374653676 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 119530936416 (111.32 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 17341.5 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 8737
telemt_upstream_connect_success_total 8737
telemt_upstream_connect_attempts_per_request{bucket="1"} 8737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 7845
telemt_me_reconnect_success_total 7801
telemt_me_reader_eof_total 8567
telemt_me_idle_close_by_peer_total 8567
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 7880
telemt_me_writer_restored_same_endpoint_total 7801
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```