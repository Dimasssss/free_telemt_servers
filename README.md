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

# Server Metrics 2026-03-15 15:59:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 63909.7 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292020
telemt_connections_bad_total 2784
telemt_handshake_timeouts_total 8984
telemt_upstream_connect_attempt_total 15879
telemt_upstream_connect_success_total 15796
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16003
telemt_me_reconnect_success_total 12617
telemt_me_reader_eof_total 13437
telemt_me_idle_close_by_peer_total 13437
telemt_me_route_drop_no_conn_total 449398
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329685
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1761
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1056
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 749
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 12854
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12583
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 268788
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 5744835712 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 224267627632 (208.87 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 63916.1 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111724
telemt_connections_bad_total 2814
telemt_handshake_timeouts_total 10662
telemt_upstream_connect_attempt_total 17534
telemt_upstream_connect_success_total 17534
telemt_upstream_connect_attempts_per_request{bucket="1"} 17534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16672
telemt_me_reconnect_success_total 14313
telemt_me_reader_eof_total 15299
telemt_me_idle_close_by_peer_total 15299
telemt_me_route_drop_no_conn_total 46002
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94895
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14555
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14297
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 94879
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 1858943528 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 48207514832 (44.90 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 63908.5 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119026
telemt_connections_bad_total 1664
telemt_handshake_timeouts_total 3045
telemt_upstream_connect_attempt_total 18894
telemt_upstream_connect_success_total 18886
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 18894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23001
telemt_me_reconnect_success_total 15651
telemt_me_reader_eof_total 16791
telemt_me_idle_close_by_peer_total 16791
telemt_me_route_drop_no_conn_total 46002
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103330
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 16026
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 15643
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 103228
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 10383458776 (9.67 GB)
telemt_user_octets_to_client{user="hello"} 59700331560 (55.60 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 63908.2 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158973
telemt_connections_bad_total 879
telemt_handshake_timeouts_total 968
telemt_upstream_connect_attempt_total 15403
telemt_upstream_connect_success_total 15395
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12290
telemt_me_reconnect_success_total 12214
telemt_me_reader_eof_total 12980
telemt_me_idle_close_by_peer_total 12980
telemt_me_route_drop_no_conn_total 61875
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146134
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 520
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 343
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 12358
telemt_me_writer_restored_same_endpoint_total 12203
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 146047
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 2791427548 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 69065045312 (64.32 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 38979.8 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95464
telemt_connections_bad_total 22416
telemt_handshake_timeouts_total 2172
telemt_upstream_connect_attempt_total 12159
telemt_upstream_connect_success_total 12087
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 12159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 104373
telemt_me_reconnect_success_total 9935
telemt_me_reader_eof_total 10392
telemt_me_idle_close_by_peer_total 10392
telemt_me_route_drop_no_conn_total 32525
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68588
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 159
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 9980
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 9831
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 68724
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 1097167337 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 28371781691 (26.42 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 63908.1 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401647
telemt_connections_bad_total 51091
telemt_handshake_timeouts_total 3397
telemt_upstream_connect_attempt_total 13724
telemt_upstream_connect_success_total 13643
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 13724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6904
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11733
telemt_me_reconnect_success_total 10437
telemt_me_reader_eof_total 11094
telemt_me_idle_close_by_peer_total 11094
telemt_me_route_drop_no_conn_total 228163
telemt_me_route_drop_channel_closed_total 53
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355141
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 307
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10581
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10410
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 332667
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 8549230224 (7.96 GB)
telemt_user_octets_to_client{user="hello"} 175076227636 (163.05 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 77
```