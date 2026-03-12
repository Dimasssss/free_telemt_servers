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

# Server Metrics 2026-03-12 18:42:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 40123.2 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204206
telemt_connections_bad_total 2610
telemt_handshake_timeouts_total 4960
telemt_upstream_connect_attempt_total 10227
telemt_upstream_connect_success_total 10183
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 10227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 1422
telemt_me_reconnect_attempts_total 11573
telemt_me_reconnect_success_total 8116
telemt_me_reader_eof_total 8598
telemt_me_idle_close_by_peer_total 8597
telemt_me_route_drop_no_conn_total 60967
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171705
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 636
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8319
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8100
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 171664
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 3033970820 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 74441295596 (69.33 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 40016.1 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89310
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 703
telemt_upstream_connect_attempt_total 20087
telemt_upstream_connect_success_total 19827
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 20087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 332
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 328
telemt_me_reconnect_attempts_total 43034
telemt_me_reconnect_success_total 9106
telemt_me_reader_eof_total 10338
telemt_me_idle_close_by_peer_total 10338
telemt_me_route_drop_no_conn_total 35393
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76285
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10238
telemt_me_refill_failed_total 1059
telemt_me_writer_restored_same_endpoint_total 9091
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1132
telemt_user_connections_total{user="hello"} 84952
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 909891592 (867.74 MB)
telemt_user_octets_to_client{user="hello"} 24217248339 (22.55 GB)
telemt_user_msgs_from_client{user="hello"} 135145
telemt_user_msgs_to_client{user="hello"} 1017437
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 39979.6 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116001
telemt_connections_bad_total 1513
telemt_handshake_timeouts_total 2129
telemt_upstream_connect_attempt_total 11260
telemt_upstream_connect_success_total 11260
telemt_upstream_connect_attempts_per_request{bucket="1"} 11260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 10305
telemt_me_reconnect_success_total 9173
telemt_me_reader_eof_total 9733
telemt_me_idle_close_by_peer_total 9733
telemt_me_route_drop_no_conn_total 43695
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107678
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9295
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 9153
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 107650
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2436158116 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 54859073008 (51.09 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 39955.4 (11h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167577
telemt_connections_bad_total 13108
telemt_handshake_timeouts_total 1201
telemt_upstream_connect_attempt_total 21750
telemt_upstream_connect_success_total 12153
telemt_upstream_connect_fail_total 9597
telemt_upstream_connect_attempts_per_request{bucket="1"} 21750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9597
telemt_me_keepalive_timeout_total 2412
telemt_me_reconnect_attempts_total 38417
telemt_me_reconnect_success_total 7236
telemt_me_reader_eof_total 8405
telemt_me_idle_close_by_peer_total 8398
telemt_me_route_drop_no_conn_total 56903
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133364
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 449
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 8340
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 7226
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1104
telemt_user_connections_total{user="hello"} 136122
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2521908414 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 54839344161 (51.07 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 39911.9 (11h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253887
telemt_connections_bad_total 2019
telemt_handshake_timeouts_total 2131
telemt_upstream_connect_attempt_total 8498
telemt_upstream_connect_success_total 8454
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 8498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 468
telemt_me_reconnect_attempts_total 10020
telemt_me_reconnect_success_total 6416
telemt_me_reader_eof_total 6839
telemt_me_idle_close_by_peer_total 6838
telemt_me_route_drop_no_conn_total 116911
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251695
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6610
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6409
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 241620
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 4225011704 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 111582256000 (103.92 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 56
```