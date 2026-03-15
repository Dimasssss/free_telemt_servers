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

# Server Metrics 2026-03-15 20:04:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 78613.9 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369122
telemt_connections_bad_total 4484
telemt_handshake_timeouts_total 13622
telemt_upstream_connect_attempt_total 18857
telemt_upstream_connect_success_total 18763
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 18857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 18236
telemt_me_reconnect_success_total 14835
telemt_me_reader_eof_total 15818
telemt_me_idle_close_by_peer_total 15818
telemt_me_route_drop_no_conn_total 476280
telemt_me_route_drop_channel_closed_total 77
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398047
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1953
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1187
telemt_desync_frames_bucket_total{bucket="1_2"} 370
telemt_desync_frames_bucket_total{bucket="3_10"} 757
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 15104
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14801
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 337110
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 7582811424 (7.06 GB)
telemt_user_octets_to_client{user="hello"} 259439495452 (241.62 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 78620.8 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151742
telemt_connections_bad_total 2859
telemt_handshake_timeouts_total 13170
telemt_upstream_connect_attempt_total 21545
telemt_upstream_connect_success_total 21497
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 21545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 538
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1037
telemt_me_reconnect_attempts_total 19641
telemt_me_reconnect_success_total 17192
telemt_me_reader_eof_total 18325
telemt_me_idle_close_by_peer_total 18324
telemt_me_route_drop_no_conn_total 63337
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129268
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 17525
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 17176
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 129540
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 2394206089 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 64684848764 (60.24 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 78613.2 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152285
telemt_connections_bad_total 1726
telemt_handshake_timeouts_total 3381
telemt_upstream_connect_attempt_total 22625
telemt_upstream_connect_success_total 22617
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 22625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25997
telemt_me_reconnect_success_total 18632
telemt_me_reader_eof_total 20011
telemt_me_idle_close_by_peer_total 20011
telemt_me_route_drop_no_conn_total 60016
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134888
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 19047
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 18624
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 415
telemt_user_connections_total{user="hello"} 134775
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 10862121848 (10.12 GB)
telemt_user_octets_to_client{user="hello"} 75055638128 (69.90 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 78612.9 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218389
telemt_connections_bad_total 1177
telemt_handshake_timeouts_total 1575
telemt_upstream_connect_attempt_total 18431
telemt_upstream_connect_success_total 18415
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 18431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9506
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 14578
telemt_me_reconnect_success_total 14489
telemt_me_reader_eof_total 15435
telemt_me_idle_close_by_peer_total 15435
telemt_me_route_drop_no_conn_total 80488
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201146
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 726
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 461
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 14662
telemt_me_writer_restored_same_endpoint_total 14478
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 201064
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 3750341148 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 91366359044 (85.09 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 53684.3 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131122
telemt_connections_bad_total 26093
telemt_handshake_timeouts_total 2504
telemt_upstream_connect_attempt_total 15758
telemt_upstream_connect_success_total 15660
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 15757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 107254
telemt_me_reconnect_success_total 12803
telemt_me_reader_eof_total 13468
telemt_me_idle_close_by_peer_total 13468
telemt_me_route_drop_no_conn_total 44499
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98923
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 309
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12889
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 12699
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 99053
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 1593146433 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 38541833767 (35.89 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 78612.2 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533945
telemt_connections_bad_total 58050
telemt_handshake_timeouts_total 4288
telemt_upstream_connect_attempt_total 16751
telemt_upstream_connect_success_total 16656
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 16751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 14010
telemt_me_reconnect_success_total 12700
telemt_me_reader_eof_total 13500
telemt_me_idle_close_by_peer_total 13500
telemt_me_route_drop_no_conn_total 383986
telemt_me_route_drop_channel_closed_total 91
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520163
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 322
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 12876
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12673
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 451733
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 11467932936 (10.68 GB)
telemt_user_octets_to_client{user="hello"} 258433939924 (240.69 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 66
```