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

# Server Metrics 2026-03-17 02:20:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 27283.4 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145917
telemt_connections_bad_total 2329
telemt_handshake_timeouts_total 5318
telemt_upstream_connect_attempt_total 5890
telemt_upstream_connect_success_total 5852
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 5890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4486
telemt_me_reconnect_success_total 4471
telemt_me_reader_eof_total 4753
telemt_me_idle_close_by_peer_total 4753
telemt_me_route_drop_no_conn_total 45169
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132104
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 724
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 160
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4507
telemt_me_writer_restored_same_endpoint_total 4450
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 132038
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 1844335956 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 60564533748 (56.41 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 27534.8 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83222
telemt_connections_bad_total 1342
telemt_handshake_timeouts_total 2918
telemt_upstream_connect_attempt_total 7306
telemt_upstream_connect_success_total 7208
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 7305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_reconnect_attempts_total 6999
telemt_me_reconnect_success_total 5832
telemt_me_reader_eof_total 6150
telemt_me_idle_close_by_peer_total 6150
telemt_me_route_drop_no_conn_total 34577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75545
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 176
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5929
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5816
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 75488
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 1125641484 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 35421601476 (32.99 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 27311.2 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53361
telemt_connections_bad_total 625
telemt_handshake_timeouts_total 1848
telemt_upstream_connect_attempt_total 7398
telemt_upstream_connect_success_total 7354
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 7398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 5993
telemt_me_reconnect_success_total 5959
telemt_me_reader_eof_total 6369
telemt_me_idle_close_by_peer_total 6369
telemt_me_route_drop_no_conn_total 16664
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44998
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6038
telemt_me_writer_restored_same_endpoint_total 5948
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 44982
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 5540270700 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 16971906140 (15.81 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 27370.5 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83123
telemt_connections_bad_total 3086
telemt_handshake_timeouts_total 756
telemt_upstream_connect_attempt_total 6418
telemt_upstream_connect_success_total 6361
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 6418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 5003
telemt_me_reconnect_success_total 4969
telemt_me_reader_eof_total 5272
telemt_me_idle_close_by_peer_total 5272
telemt_me_route_drop_no_conn_total 28648
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76968
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5039
telemt_me_writer_restored_same_endpoint_total 4962
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 76952
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 911982672 (869.73 MB)
telemt_user_octets_to_client{user="hello"} 36533751152 (34.02 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 27342.5 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63402
telemt_connections_bad_total 15579
telemt_handshake_timeouts_total 535
telemt_upstream_connect_attempt_total 8166
telemt_upstream_connect_success_total 8060
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 8166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_reconnect_attempts_total 8918
telemt_me_reconnect_success_total 6672
telemt_me_reader_eof_total 7029
telemt_me_idle_close_by_peer_total 7029
telemt_me_route_drop_no_conn_total 18029
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45463
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6847
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 6664
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 45458
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 532122580 (507.47 MB)
telemt_user_octets_to_client{user="hello"} 14592938084 (13.59 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 27503.3 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154156
telemt_connections_bad_total 4615
telemt_handshake_timeouts_total 1052
telemt_upstream_connect_attempt_total 5681
telemt_upstream_connect_success_total 5649
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 4287
telemt_me_reconnect_success_total 4273
telemt_me_reader_eof_total 4579
telemt_me_idle_close_by_peer_total 4579
telemt_me_route_drop_no_conn_total 174590
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220863
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4333
telemt_me_writer_restored_same_endpoint_total 4263
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 143120
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 2336210340 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 117983966264 (109.88 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 15509.9 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 7816
telemt_upstream_connect_success_total 7816
telemt_upstream_connect_attempts_per_request{bucket="1"} 7816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 7010
telemt_me_reconnect_success_total 6968
telemt_me_reader_eof_total 7649
telemt_me_idle_close_by_peer_total 7649
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 7039
telemt_me_writer_restored_same_endpoint_total 6968
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```