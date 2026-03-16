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

# Server Metrics 2026-03-16 05:51:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 113832.6 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491811
telemt_connections_bad_total 5502
telemt_handshake_timeouts_total 17939
telemt_upstream_connect_attempt_total 27066
telemt_upstream_connect_success_total 26942
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 27066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24732
telemt_me_reconnect_success_total 21303
telemt_me_reader_eof_total 22792
telemt_me_idle_close_by_peer_total 22792
telemt_me_route_drop_no_conn_total 510998
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509134
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2483
telemt_desync_full_logged_total 991
telemt_desync_suppressed_total 1492
telemt_desync_frames_bucket_total{bucket="1_2"} 504
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 1006
telemt_pool_swap_total 110
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21638
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21269
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 447980
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 8950949112 (8.34 GB)
telemt_user_octets_to_client{user="hello"} 304635265636 (283.71 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 113838.7 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198270
telemt_connections_bad_total 3001
telemt_handshake_timeouts_total 14842
telemt_upstream_connect_attempt_total 30765
telemt_upstream_connect_success_total 30690
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 30765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 31548
telemt_me_reconnect_success_total 24634
telemt_me_reader_eof_total 26412
telemt_me_idle_close_by_peer_total 26411
telemt_me_route_drop_no_conn_total 99994
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173155
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 25191
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 24618
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 557
telemt_user_connections_total{user="hello"} 172698
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 3866596157 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 89611607268 (83.46 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 113831.4 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218796
telemt_connections_bad_total 3852
telemt_handshake_timeouts_total 4186
telemt_upstream_connect_attempt_total 31920
telemt_upstream_connect_success_total 31912
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 33605
telemt_me_reconnect_success_total 26211
telemt_me_reader_eof_total 28239
telemt_me_idle_close_by_peer_total 28238
telemt_me_route_drop_no_conn_total 77505
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173457
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 26697
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 26203
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 173181
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 16624211045 (15.48 GB)
telemt_user_octets_to_client{user="hello"} 106372498508 (99.07 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 113831.0 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290735
telemt_connections_bad_total 1285
telemt_handshake_timeouts_total 2660
telemt_upstream_connect_attempt_total 26504
telemt_upstream_connect_success_total 26478
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 26504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 20962
telemt_me_reconnect_success_total 20836
telemt_me_reader_eof_total 22255
telemt_me_idle_close_by_peer_total 22254
telemt_me_route_drop_no_conn_total 105628
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267125
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 942
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 21095
telemt_me_writer_restored_same_endpoint_total 20825
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 267014
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 4496165908 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 117635570740 (109.56 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 88902.3 (24h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195598
telemt_connections_bad_total 34636
telemt_handshake_timeouts_total 3451
telemt_upstream_connect_attempt_total 25401
telemt_upstream_connect_success_total 25262
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 25401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 115168
telemt_me_reconnect_success_total 20690
telemt_me_reader_eof_total 21980
telemt_me_idle_close_by_peer_total 21980
telemt_me_route_drop_no_conn_total 61657
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152655
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 383
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 20856
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 20586
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 152288
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 2056099421 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 66996009683 (62.39 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 113830.1 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 734460
telemt_connections_bad_total 64404
telemt_handshake_timeouts_total 5495
telemt_upstream_connect_attempt_total 24097
telemt_upstream_connect_success_total 23969
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 24097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19638
telemt_me_reconnect_success_total 18300
telemt_me_reader_eof_total 19545
telemt_me_idle_close_by_peer_total 19545
telemt_me_route_drop_no_conn_total 614848
telemt_me_route_drop_channel_closed_total 99
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 742888
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 18553
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18273
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 601554
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 13634852584 (12.70 GB)
telemt_user_octets_to_client{user="hello"} 369045619800 (343.70 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 65
```