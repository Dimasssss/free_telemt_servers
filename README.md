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

# Server Metrics 2026-03-13 08:19:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 89170.0 (24h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345972
telemt_connections_bad_total 3175
telemt_handshake_timeouts_total 7567
telemt_upstream_connect_attempt_total 22303
telemt_upstream_connect_success_total 22198
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 22303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1660
telemt_me_reconnect_attempts_total 21229
telemt_me_reconnect_success_total 17723
telemt_me_reader_eof_total 18956
telemt_me_idle_close_by_peer_total 18955
telemt_me_route_drop_no_conn_total 108025
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295337
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 976
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 615
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 18021
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17707
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 295028
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 4857560696 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 135394280544 (126.10 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 89063.7 (24h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157622
telemt_connections_bad_total 1493
telemt_handshake_timeouts_total 1204
telemt_upstream_connect_attempt_total 45148
telemt_upstream_connect_success_total 44537
telemt_upstream_connect_fail_total 611
telemt_upstream_connect_attempts_per_request{bucket="1"} 45148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 512
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 611
telemt_me_keepalive_timeout_total 682
telemt_me_reconnect_attempts_total 78980
telemt_me_reconnect_success_total 23609
telemt_me_reader_eof_total 26031
telemt_me_idle_close_by_peer_total 26031
telemt_me_route_drop_no_conn_total 59378
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132326
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 25530
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 23594
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1921
telemt_user_connections_total{user="hello"} 148817
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 1544027600 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 47780617431 (44.50 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 89027.5 (24h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190079
telemt_connections_bad_total 1986
telemt_handshake_timeouts_total 3311
telemt_upstream_connect_attempt_total 24096
telemt_upstream_connect_success_total 24094
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 24096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 574
telemt_me_reconnect_attempts_total 20804
telemt_me_reconnect_success_total 19625
telemt_me_reader_eof_total 21048
telemt_me_idle_close_by_peer_total 21048
telemt_me_route_drop_no_conn_total 73147
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177772
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 19839
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19605
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 177702
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 6645453952 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 75210712472 (70.05 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 89003.1 (24h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275766
telemt_connections_bad_total 13647
telemt_handshake_timeouts_total 2039
telemt_upstream_connect_attempt_total 36899
telemt_upstream_connect_success_total 26938
telemt_upstream_connect_fail_total 9961
telemt_upstream_connect_attempts_per_request{bucket="1"} 36899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9961
telemt_me_keepalive_timeout_total 3381
telemt_me_reconnect_attempts_total 71191
telemt_me_reconnect_success_total 19646
telemt_me_reader_eof_total 21890
telemt_me_idle_close_by_peer_total 21883
telemt_me_route_drop_no_conn_total 99464
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234266
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 859
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 21512
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19636
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1866
telemt_user_connections_total{user="hello"} 236992
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 5264903710 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 89645777865 (83.49 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 39174.5 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49191
telemt_connections_bad_total 7979
telemt_handshake_timeouts_total 410
telemt_upstream_connect_attempt_total 13489
telemt_upstream_connect_success_total 13352
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 13489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 319
telemt_me_reconnect_attempts_total 12354
telemt_me_reconnect_success_total 11384
telemt_me_reader_eof_total 12102
telemt_me_idle_close_by_peer_total 12102
telemt_me_route_drop_no_conn_total 14664
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39438
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11513
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 11366
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 39437
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 280541236 (267.54 MB)
telemt_user_octets_to_client{user="hello"} 11315578912 (10.54 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 88959.6 (24h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471664
telemt_connections_bad_total 13322
telemt_handshake_timeouts_total 4127
telemt_upstream_connect_attempt_total 18801
telemt_upstream_connect_success_total 18700
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1529
telemt_me_reconnect_attempts_total 17935
telemt_me_reconnect_success_total 14294
telemt_me_reader_eof_total 15353
telemt_me_idle_close_by_peer_total 15350
telemt_me_route_drop_no_conn_total 240210
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461480
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 376
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 14590
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14287
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 437404
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 8080038252 (7.53 GB)
telemt_user_octets_to_client{user="hello"} 251296417684 (234.04 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 67
```