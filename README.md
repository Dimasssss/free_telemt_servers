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

# Server Metrics 2026-03-15 18:37:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 73406.3 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345054
telemt_connections_bad_total 4198
telemt_handshake_timeouts_total 11636
telemt_upstream_connect_attempt_total 17770
telemt_upstream_connect_success_total 17681
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 17769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17415
telemt_me_reconnect_success_total 14015
telemt_me_reader_eof_total 14930
telemt_me_idle_close_by_peer_total 14930
telemt_me_route_drop_no_conn_total 465800
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376949
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 749
telemt_desync_suppressed_total 1146
telemt_desync_frames_bucket_total{bucket="1_2"} 358
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 801
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14273
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13981
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 316049
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 6441501012 (6.00 GB)
telemt_user_octets_to_client{user="hello"} 245219122220 (228.38 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 73413.6 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138692
telemt_connections_bad_total 2839
telemt_handshake_timeouts_total 12516
telemt_upstream_connect_attempt_total 19820
telemt_upstream_connect_success_total 19820
telemt_upstream_connect_attempts_per_request{bucket="1"} 19820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 337
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18480
telemt_me_reconnect_success_total 16113
telemt_me_reader_eof_total 17231
telemt_me_idle_close_by_peer_total 17230
telemt_me_route_drop_no_conn_total 57511
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117708
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 16402
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 16097
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 117688
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 2210670276 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 58866374824 (54.82 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 73405.2 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142060
telemt_connections_bad_total 1700
telemt_handshake_timeouts_total 3304
telemt_upstream_connect_attempt_total 21386
telemt_upstream_connect_success_total 21378
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 21386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25016
telemt_me_reconnect_success_total 17656
telemt_me_reader_eof_total 18952
telemt_me_idle_close_by_peer_total 18952
telemt_me_route_drop_no_conn_total 55625
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125139
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 18054
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17648
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 125031
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 10765440020 (10.03 GB)
telemt_user_octets_to_client{user="hello"} 69247414980 (64.49 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 73405.1 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197649
telemt_connections_bad_total 963
telemt_handshake_timeouts_total 1343
telemt_upstream_connect_attempt_total 17349
telemt_upstream_connect_success_total 17335
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 17349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13755
telemt_me_reconnect_success_total 13672
telemt_me_reader_eof_total 14552
telemt_me_idle_close_by_peer_total 14552
telemt_me_route_drop_no_conn_total 74449
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182092
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 644
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 13835
telemt_me_writer_restored_same_endpoint_total 13661
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 182004
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 3366506524 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 85159801776 (79.31 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 48476.6 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119516
telemt_connections_bad_total 24577
telemt_handshake_timeouts_total 2465
telemt_upstream_connect_attempt_total 14336
telemt_upstream_connect_success_total 14252
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 14336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 106103
telemt_me_reconnect_success_total 11656
telemt_me_reader_eof_total 12247
telemt_me_idle_close_by_peer_total 12247
telemt_me_route_drop_no_conn_total 40864
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89151
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 280
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 11727
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11552
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 89283
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 1504108309 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 34559363343 (32.19 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 73405.0 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494900
telemt_connections_bad_total 57828
telemt_handshake_timeouts_total 4019
telemt_upstream_connect_attempt_total 15783
telemt_upstream_connect_success_total 15692
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13305
telemt_me_reconnect_success_total 12000
telemt_me_reader_eof_total 12749
telemt_me_idle_close_by_peer_total 12749
telemt_me_route_drop_no_conn_total 317379
telemt_me_route_drop_channel_closed_total 81
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 456333
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 12169
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11973
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 414910
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 10606062576 (9.88 GB)
telemt_user_octets_to_client{user="hello"} 229067657192 (213.34 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 58
```