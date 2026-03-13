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

# Server Metrics 2026-03-13 07:13:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 85177.6 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325276
telemt_connections_bad_total 3142
telemt_handshake_timeouts_total 6939
telemt_upstream_connect_attempt_total 21412
telemt_upstream_connect_success_total 21314
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 21412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1648
telemt_me_reconnect_attempts_total 20545
telemt_me_reconnect_success_total 17042
telemt_me_reader_eof_total 18225
telemt_me_idle_close_by_peer_total 18224
telemt_me_route_drop_no_conn_total 102387
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276234
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 938
telemt_desync_full_logged_total 348
telemt_desync_suppressed_total 590
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 409
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 17335
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17026
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 275934
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 4638100720 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 130340001104 (121.39 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 85070.6 (23h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148568
telemt_connections_bad_total 1422
telemt_handshake_timeouts_total 1146
telemt_upstream_connect_attempt_total 44138
telemt_upstream_connect_success_total 43556
telemt_upstream_connect_fail_total 582
telemt_upstream_connect_attempts_per_request{bucket="1"} 44138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 510
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 582
telemt_me_keepalive_timeout_total 656
telemt_me_reconnect_attempts_total 73022
telemt_me_reconnect_success_total 22804
telemt_me_reader_eof_total 25054
telemt_me_idle_close_by_peer_total 25054
telemt_me_route_drop_no_conn_total 56177
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124133
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
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
telemt_me_writer_removed_unexpected_total 24553
telemt_me_refill_failed_total 1567
telemt_me_writer_restored_same_endpoint_total 22789
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1749
telemt_user_connections_total{user="hello"} 140626
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 1447874780 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 45473306927 (42.35 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 85034.2 (23h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180328
telemt_connections_bad_total 1951
telemt_handshake_timeouts_total 2921
telemt_upstream_connect_attempt_total 23174
telemt_upstream_connect_success_total 23172
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 556
telemt_me_reconnect_attempts_total 20054
telemt_me_reconnect_success_total 18878
telemt_me_reader_eof_total 20241
telemt_me_idle_close_by_peer_total 20241
telemt_me_route_drop_no_conn_total 69712
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168753
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
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 19083
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18858
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 168681
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 3001453096 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 73947440300 (68.87 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 85009.8 (23h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258826
telemt_connections_bad_total 13613
telemt_handshake_timeouts_total 1968
telemt_upstream_connect_attempt_total 35870
telemt_upstream_connect_success_total 25925
telemt_upstream_connect_fail_total 9945
telemt_upstream_connect_attempts_per_request{bucket="1"} 35870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9945
telemt_me_keepalive_timeout_total 3357
telemt_me_reconnect_attempts_total 70353
telemt_me_reconnect_success_total 18813
telemt_me_reader_eof_total 21020
telemt_me_idle_close_by_peer_total 21013
telemt_me_route_drop_no_conn_total 93521
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218759
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 700
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 499
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 20667
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18803
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1854
telemt_user_connections_total{user="hello"} 221492
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 4678953910 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 85279896129 (79.42 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 35181.5 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42362
telemt_connections_bad_total 7258
telemt_handshake_timeouts_total 376
telemt_upstream_connect_attempt_total 11961
telemt_upstream_connect_success_total 11838
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 11961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 11035
telemt_me_reconnect_success_total 10067
telemt_me_reader_eof_total 10738
telemt_me_idle_close_by_peer_total 10738
telemt_me_route_drop_no_conn_total 12007
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33667
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10188
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10049
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 33667
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 246604120 (235.18 MB)
telemt_user_octets_to_client{user="hello"} 10706153208 (9.97 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 84966.4 (23h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438851
telemt_connections_bad_total 8907
telemt_handshake_timeouts_total 3312
telemt_upstream_connect_attempt_total 18097
telemt_upstream_connect_success_total 17999
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 18097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 1501
telemt_me_reconnect_attempts_total 17407
telemt_me_reconnect_success_total 13770
telemt_me_reader_eof_total 14790
telemt_me_idle_close_by_peer_total 14787
telemt_me_route_drop_no_conn_total 193556
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423439
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 14057
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13763
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 411670
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 7521811020 (7.01 GB)
telemt_user_octets_to_client{user="hello"} 238460813764 (222.08 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 55
```