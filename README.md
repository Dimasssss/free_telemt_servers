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

# Server Metrics 2026-03-15 13:36:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 55336.1 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247088
telemt_connections_bad_total 2273
telemt_handshake_timeouts_total 5456
telemt_upstream_connect_attempt_total 13923
telemt_upstream_connect_success_total 13849
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 13923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 14449
telemt_me_reconnect_success_total 11071
telemt_me_reader_eof_total 11827
telemt_me_idle_close_by_peer_total 11827
telemt_me_route_drop_no_conn_total 433326
telemt_me_route_drop_channel_closed_total 66
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291071
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1667
telemt_desync_full_logged_total 659
telemt_desync_suppressed_total 1008
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 655
telemt_desync_frames_bucket_total{bucket="gt_10"} 717
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11289
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11040
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 230176
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 5069801588 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 203687331500 (189.70 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 55342.3 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90275
telemt_connections_bad_total 2746
telemt_handshake_timeouts_total 8330
telemt_upstream_connect_attempt_total 15243
telemt_upstream_connect_success_total 15243
telemt_upstream_connect_attempts_per_request{bucket="1"} 15243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 14782
telemt_me_reconnect_success_total 12438
telemt_me_reader_eof_total 13310
telemt_me_idle_close_by_peer_total 13310
telemt_me_route_drop_no_conn_total 38437
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76432
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12649
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12422
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 76428
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 1516565204 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 37040386444 (34.50 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 55335.2 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92544
telemt_connections_bad_total 1611
telemt_handshake_timeouts_total 2736
telemt_upstream_connect_attempt_total 16235
telemt_upstream_connect_success_total 16227
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 16235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 15570
telemt_me_reconnect_success_total 13418
telemt_me_reader_eof_total 14331
telemt_me_idle_close_by_peer_total 14331
telemt_me_route_drop_no_conn_total 36073
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84248
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 13613
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 13410
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 84154
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 9997342864 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 51323841476 (47.80 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 55334.7 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127769
telemt_connections_bad_total 552
telemt_handshake_timeouts_total 824
telemt_upstream_connect_attempt_total 13026
telemt_upstream_connect_success_total 13023
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 13026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 10308
telemt_me_reconnect_success_total 10246
telemt_me_reader_eof_total 10922
telemt_me_idle_close_by_peer_total 10922
telemt_me_route_drop_no_conn_total 49737
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116356
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 402
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10363
telemt_me_writer_restored_same_endpoint_total 10235
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 116273
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 2166048052 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 60196112364 (56.06 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 30406.1 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73735
telemt_connections_bad_total 20740
telemt_handshake_timeouts_total 1395
telemt_upstream_connect_attempt_total 9676
telemt_upstream_connect_success_total 9612
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 9676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 102337
telemt_me_reconnect_success_total 7912
telemt_me_reader_eof_total 8264
telemt_me_idle_close_by_peer_total 8264
telemt_me_route_drop_no_conn_total 24668
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49965
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 7918
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 7808
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 50101
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 764278945 (728.87 MB)
telemt_user_octets_to_client{user="hello"} 20158363203 (18.77 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 55334.3 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326661
telemt_connections_bad_total 47905
telemt_handshake_timeouts_total 2587
telemt_upstream_connect_attempt_total 11816
telemt_upstream_connect_success_total 11745
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 11816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 9019
telemt_me_reconnect_success_total 8956
telemt_me_reader_eof_total 9527
telemt_me_idle_close_by_peer_total 9527
telemt_me_route_drop_no_conn_total 149789
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266990
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 278
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9039
telemt_me_writer_restored_same_endpoint_total 8929
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 264854
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 5844841516 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 129287407376 (120.41 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 66
```