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

# Server Metrics 2026-03-14 10:31:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 183478.7 (50h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 715685
telemt_connections_bad_total 33780
telemt_handshake_timeouts_total 13852
telemt_upstream_connect_attempt_total 46771
telemt_upstream_connect_success_total 46536
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 46771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 6022
telemt_me_reconnect_attempts_total 42787
telemt_me_reconnect_success_total 37026
telemt_me_reader_eof_total 39575
telemt_me_idle_close_by_peer_total 39574
telemt_me_route_drop_no_conn_total 236738
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 612949
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2419
telemt_desync_full_logged_total 811
telemt_desync_suppressed_total 1608
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 892
telemt_desync_frames_bucket_total{bucket="gt_10"} 1011
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 37601
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37006
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 575
telemt_user_connections_total{user="hello"} 612828
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 17411477390 (16.22 GB)
telemt_user_octets_to_client{user="hello"} 292763336592 (272.66 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 183372.6 (50h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357584
telemt_connections_bad_total 2825
telemt_handshake_timeouts_total 3176
telemt_upstream_connect_attempt_total 154161
telemt_upstream_connect_success_total 152808
telemt_upstream_connect_fail_total 1353
telemt_upstream_connect_attempts_per_request{bucket="1"} 154161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2461
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1353
telemt_me_keepalive_timeout_total 5468
telemt_me_reconnect_attempts_total 188664
telemt_me_reconnect_success_total 40377
telemt_me_reader_eof_total 46076
telemt_me_idle_close_by_peer_total 46076
telemt_me_route_drop_no_conn_total 123020
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234402
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 45394
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 40360
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5017
telemt_user_connections_total{user="hello"} 337506
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 3452267551 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 107598684511 (100.21 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 183336.1 (50h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414468
telemt_connections_bad_total 3268
telemt_handshake_timeouts_total 35815
telemt_upstream_connect_attempt_total 48688
telemt_upstream_connect_success_total 48679
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3892
telemt_me_reconnect_attempts_total 40809
telemt_me_reconnect_success_total 39503
telemt_me_reader_eof_total 42460
telemt_me_idle_close_by_peer_total 42460
telemt_me_route_drop_no_conn_total 150615
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360705
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 39978
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39482
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 360436
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 13969785388 (13.01 GB)
telemt_user_octets_to_client{user="hello"} 158581015672 (147.69 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 183312.0 (50h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523515
telemt_connections_bad_total 16713
telemt_handshake_timeouts_total 5230
telemt_upstream_connect_attempt_total 79061
telemt_upstream_connect_success_total 68389
telemt_upstream_connect_fail_total 10672
telemt_upstream_connect_attempts_per_request{bucket="1"} 79061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10672
telemt_me_keepalive_timeout_total 5636
telemt_me_reconnect_attempts_total 152526
telemt_me_reconnect_success_total 40227
telemt_me_reader_eof_total 45028
telemt_me_idle_close_by_peer_total 45020
telemt_me_route_drop_no_conn_total 189749
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448089
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2014
telemt_desync_full_logged_total 596
telemt_desync_suppressed_total 1418
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 774
telemt_desync_frames_bucket_total{bucket="gt_10"} 762
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 44191
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 40217
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3964
telemt_user_connections_total{user="hello"} 466956
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 9994187659 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 193139203952 (179.87 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 133483.4 (37h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222634
telemt_connections_bad_total 34500
telemt_handshake_timeouts_total 1992
telemt_upstream_connect_attempt_total 46999
telemt_upstream_connect_success_total 46533
telemt_upstream_connect_fail_total 466
telemt_upstream_connect_attempts_per_request{bucket="1"} 46999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 466
telemt_me_keepalive_timeout_total 2796
telemt_me_reconnect_attempts_total 50867
telemt_me_reconnect_success_total 34983
telemt_me_reader_eof_total 37418
telemt_me_idle_close_by_peer_total 37418
telemt_me_route_drop_no_conn_total 67359
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175285
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 35801
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34965
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 818
telemt_user_connections_total{user="hello"} 180042
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 2677853877 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 84020147631 (78.25 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 183268.1 (50h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1062160
telemt_connections_bad_total 36980
telemt_handshake_timeouts_total 26936
telemt_upstream_connect_attempt_total 38307
telemt_upstream_connect_success_total 38105
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 38307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 4870
telemt_me_reconnect_attempts_total 33731
telemt_me_reconnect_success_total 29043
telemt_me_reader_eof_total 31143
telemt_me_idle_close_by_peer_total 31140
telemt_me_route_drop_no_conn_total 497096
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 984655
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 29553
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29036
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 957266
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 17956271112 (16.72 GB)
telemt_user_octets_to_client{user="hello"} 481392016832 (448.33 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 68
```