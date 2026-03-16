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

# Server Metrics 2026-03-16 18:17:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 16785.5 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166427
telemt_connections_bad_total 753
telemt_handshake_timeouts_total 4200
telemt_upstream_connect_attempt_total 3550
telemt_upstream_connect_success_total 3537
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3819
telemt_me_reconnect_success_total 2649
telemt_me_reader_eof_total 2754
telemt_me_idle_close_by_peer_total 2753
telemt_me_route_drop_no_conn_total 51191
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155984
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 793
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 609
telemt_desync_frames_bucket_total{bucket="1_2"} 297
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2704
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2647
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 155898
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 2952970000 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 90045029076 (83.86 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 11564.2 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80204
telemt_connections_bad_total 642
telemt_handshake_timeouts_total 3231
telemt_upstream_connect_attempt_total 2468
telemt_upstream_connect_success_total 2455
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 5347
telemt_me_reconnect_success_total 1836
telemt_me_reader_eof_total 1983
telemt_me_idle_close_by_peer_total 1983
telemt_me_route_drop_no_conn_total 45657
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73449
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 129
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1979
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1831
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 73390
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 837143856 (798.36 MB)
telemt_user_octets_to_client{user="hello"} 21449466852 (19.98 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 16899.0 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68129
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 886
telemt_upstream_connect_attempt_total 4948
telemt_upstream_connect_success_total 4897
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 4948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 41910
telemt_me_reconnect_success_total 3024
telemt_me_reader_eof_total 3386
telemt_me_idle_close_by_peer_total 3386
telemt_me_route_drop_no_conn_total 24140
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63027
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 165
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3361
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 2980
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 63961
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 851593702 (812.14 MB)
telemt_user_octets_to_client{user="hello"} 18741405138 (17.45 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 17034.8 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132201
telemt_connections_bad_total 235
telemt_handshake_timeouts_total 1799
telemt_upstream_connect_attempt_total 3628
telemt_upstream_connect_success_total 3602
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9038
telemt_me_reconnect_success_total 2680
telemt_me_reader_eof_total 2942
telemt_me_idle_close_by_peer_total 2941
telemt_me_route_drop_no_conn_total 48151
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125520
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 675
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2914
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2676
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 125486
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 1797670448 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 31566304120 (29.40 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 14495.2 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74441
telemt_connections_bad_total 20582
telemt_handshake_timeouts_total 585
telemt_upstream_connect_attempt_total 3781
telemt_upstream_connect_success_total 3723
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 3780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 4621
telemt_me_reconnect_success_total 2958
telemt_me_reader_eof_total 3064
telemt_me_idle_close_by_peer_total 3064
telemt_me_route_drop_no_conn_total 51957
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69566
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3113
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2958
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 50609
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 2097258712 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 34103935928 (31.76 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 16605.0 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191231
telemt_connections_bad_total 2293
telemt_handshake_timeouts_total 3445
telemt_upstream_connect_attempt_total 3422
telemt_upstream_connect_success_total 3422
telemt_upstream_connect_attempts_per_request{bucket="1"} 3422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7562
telemt_me_reconnect_success_total 2533
telemt_me_reader_eof_total 2755
telemt_me_idle_close_by_peer_total 2754
telemt_me_route_drop_no_conn_total 88161
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177713
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 130
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2711
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2527
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 177375
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 3474124364 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 65877144316 (61.35 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 88
```