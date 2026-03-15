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

# Server Metrics 2026-03-15 09:36:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 40941.8 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161433
telemt_connections_bad_total 1153
telemt_handshake_timeouts_total 3919
telemt_upstream_connect_attempt_total 10138
telemt_upstream_connect_success_total 10081
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 10138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 9252
telemt_me_reconnect_success_total 8038
telemt_me_reader_eof_total 8592
telemt_me_idle_close_by_peer_total 8592
telemt_me_route_drop_no_conn_total 357228
telemt_me_route_drop_channel_closed_total 50
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205500
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1225
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 729
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8148
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8007
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 150391
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 2121637248 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 157972179552 (147.12 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 40948.9 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51892
telemt_connections_bad_total 2276
telemt_handshake_timeouts_total 3027
telemt_upstream_connect_attempt_total 11088
telemt_upstream_connect_success_total 11088
telemt_upstream_connect_attempts_per_request{bucket="1"} 11088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11336
telemt_me_reconnect_success_total 9018
telemt_me_reader_eof_total 9693
telemt_me_idle_close_by_peer_total 9693
telemt_me_route_drop_no_conn_total 24952
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44930
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9183
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9002
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 44929
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 933597748 (890.35 MB)
telemt_user_octets_to_client{user="hello"} 18005519860 (16.77 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 40941.7 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59090
telemt_connections_bad_total 503
telemt_handshake_timeouts_total 2182
telemt_upstream_connect_attempt_total 11049
telemt_upstream_connect_success_total 11048
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 9032
telemt_me_reconnect_success_total 8986
telemt_me_reader_eof_total 9674
telemt_me_idle_close_by_peer_total 9674
telemt_me_route_drop_no_conn_total 21940
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53944
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9071
telemt_me_writer_restored_same_endpoint_total 8982
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 53873
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 9225696628 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 35195188800 (32.78 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 40941.0 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74935
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 445
telemt_upstream_connect_attempt_total 9767
telemt_upstream_connect_success_total 9766
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7757
telemt_me_reconnect_success_total 7722
telemt_me_reader_eof_total 8242
telemt_me_idle_close_by_peer_total 8242
telemt_me_route_drop_no_conn_total 31931
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68079
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 139
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7800
telemt_me_writer_restored_same_endpoint_total 7711
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 68011
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1318894624 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 42975895948 (40.02 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 16012.5 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26209
telemt_connections_bad_total 3022
telemt_handshake_timeouts_total 354
telemt_upstream_connect_attempt_total 5489
telemt_upstream_connect_success_total 5441
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 5489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 98871
telemt_me_reconnect_success_total 4465
telemt_me_reader_eof_total 4606
telemt_me_idle_close_by_peer_total 4606
telemt_me_route_drop_no_conn_total 8388
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22145
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4429
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 4361
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 22285
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 214183473 (204.26 MB)
telemt_user_octets_to_client{user="hello"} 11312008143 (10.54 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 40940.2 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189206
telemt_connections_bad_total 22772
telemt_handshake_timeouts_total 1141
telemt_upstream_connect_attempt_total 8800
telemt_upstream_connect_success_total 8749
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 6732
telemt_me_reconnect_success_total 6695
telemt_me_reader_eof_total 7139
telemt_me_idle_close_by_peer_total 7139
telemt_me_route_drop_no_conn_total 90515
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160210
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6740
telemt_me_writer_restored_same_endpoint_total 6668
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 158750
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 4168758904 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 80697355224 (75.16 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 67
```