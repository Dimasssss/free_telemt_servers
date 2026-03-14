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

# Server Metrics 2026-03-14 16:02:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 9977.9 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58818
telemt_connections_bad_total 12271
telemt_handshake_timeouts_total 282
telemt_upstream_connect_attempt_total 2521
telemt_upstream_connect_success_total 2519
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 1987
telemt_me_reconnect_success_total 1963
telemt_me_reader_eof_total 2055
telemt_me_idle_close_by_peer_total 2055
telemt_me_route_drop_no_conn_total 21648
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44891
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 129
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2004
telemt_me_writer_restored_same_endpoint_total 1945
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 44826
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 758460472 (723.32 MB)
telemt_user_octets_to_client{user="hello"} 15894664520 (14.80 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 9976.0 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23022
telemt_connections_bad_total 386
telemt_handshake_timeouts_total 512
telemt_upstream_connect_attempt_total 2772
telemt_upstream_connect_success_total 2744
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 2772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 4757
telemt_me_reconnect_success_total 2197
telemt_me_reader_eof_total 2336
telemt_me_idle_close_by_peer_total 2336
telemt_me_route_drop_no_conn_total 12268
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21355
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2310
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 2192
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 21339
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 284352880 (271.18 MB)
telemt_user_octets_to_client{user="hello"} 8836926836 (8.23 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 9980.3 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23076
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 1221
telemt_upstream_connect_attempt_total 4103
telemt_upstream_connect_success_total 4068
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 97088
telemt_me_reconnect_success_total 3207
telemt_me_reader_eof_total 3367
telemt_me_idle_close_by_peer_total 3367
telemt_me_route_drop_no_conn_total 8782
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20116
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3333
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 3169
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 20406
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 594409485 (566.87 MB)
telemt_user_octets_to_client{user="hello"} 9852793270 (9.18 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 9985.3 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31571
telemt_connections_bad_total 95
telemt_handshake_timeouts_total 220
telemt_upstream_connect_attempt_total 2763
telemt_upstream_connect_success_total 2748
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2213
telemt_me_reconnect_success_total 2198
telemt_me_reader_eof_total 2263
telemt_me_idle_close_by_peer_total 2263
telemt_me_route_drop_no_conn_total 14863
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30060
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 324
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 236
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2215
telemt_me_writer_restored_same_endpoint_total 2196
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 29942
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 350559448 (334.32 MB)
telemt_user_octets_to_client{user="hello"} 11219457088 (10.45 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 9978.5 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22350
telemt_connections_bad_total 1989
telemt_handshake_timeouts_total 898
telemt_upstream_connect_attempt_total 2234
telemt_upstream_connect_success_total 2201
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 2234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 8168
telemt_me_reconnect_success_total 1655
telemt_me_reader_eof_total 1866
telemt_me_idle_close_by_peer_total 1866
telemt_me_route_drop_no_conn_total 7799
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18401
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1862
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1651
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 18396
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 147246760 (140.43 MB)
telemt_user_octets_to_client{user="hello"} 5015756852 (4.67 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 9977.9 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77267
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 602
telemt_upstream_connect_attempt_total 2250
telemt_upstream_connect_success_total 2205
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1105
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 3946
telemt_me_reconnect_success_total 1640
telemt_me_reader_eof_total 1734
telemt_me_idle_close_by_peer_total 1734
telemt_me_route_drop_no_conn_total 39187
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71755
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1727
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 1636
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 71657
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 1181199340 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 28577647556 (26.62 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 73
```