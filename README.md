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

# Server Metrics 2026-03-14 09:35:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 180122.8 (50h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697667
telemt_connections_bad_total 32632
telemt_handshake_timeouts_total 13609
telemt_upstream_connect_attempt_total 45765
telemt_upstream_connect_success_total 45532
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 45765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5887
telemt_me_reconnect_attempts_total 40863
telemt_me_reconnect_success_total 36162
telemt_me_reader_eof_total 38652
telemt_me_idle_close_by_peer_total 38651
telemt_me_route_drop_no_conn_total 230430
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 596856
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2374
telemt_desync_full_logged_total 790
telemt_desync_suppressed_total 1584
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 875
telemt_desync_frames_bucket_total{bucket="gt_10"} 994
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 36693
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 36142
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 531
telemt_user_connections_total{user="hello"} 596734
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 17245453786 (16.06 GB)
telemt_user_octets_to_client{user="hello"} 286397948224 (266.73 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 180015.7 (50h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350936
telemt_connections_bad_total 2797
telemt_handshake_timeouts_total 3066
telemt_upstream_connect_attempt_total 153303
telemt_upstream_connect_success_total 151961
telemt_upstream_connect_fail_total 1342
telemt_upstream_connect_attempts_per_request{bucket="1"} 153303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1342
telemt_me_keepalive_timeout_total 5402
telemt_me_reconnect_attempts_total 185274
telemt_me_reconnect_success_total 39709
telemt_me_reader_eof_total 45309
telemt_me_idle_close_by_peer_total 45309
telemt_me_route_drop_no_conn_total 119594
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228083
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 44
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 44636
telemt_me_refill_failed_total 4542
telemt_me_writer_restored_same_endpoint_total 39692
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4927
telemt_user_connections_total{user="hello"} 331187
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 3417533083 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 106217757727 (98.92 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 179979.2 (49h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 407429
telemt_connections_bad_total 3207
telemt_handshake_timeouts_total 35647
telemt_upstream_connect_attempt_total 47713
telemt_upstream_connect_success_total 47704
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3696
telemt_me_reconnect_attempts_total 40010
telemt_me_reconnect_success_total 38710
telemt_me_reader_eof_total 41605
telemt_me_idle_close_by_peer_total 41605
telemt_me_route_drop_no_conn_total 147753
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 354218
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 39176
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38689
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 353944
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 13752066372 (12.81 GB)
telemt_user_octets_to_client{user="hello"} 156217262796 (145.49 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 179954.9 (49h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513932
telemt_connections_bad_total 16705
telemt_handshake_timeouts_total 4814
telemt_upstream_connect_attempt_total 78047
telemt_upstream_connect_success_total 67392
telemt_upstream_connect_fail_total 10655
telemt_upstream_connect_attempts_per_request{bucket="1"} 78047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10655
telemt_me_keepalive_timeout_total 5555
telemt_me_reconnect_attempts_total 150539
telemt_me_reconnect_success_total 39413
telemt_me_reader_eof_total 44139
telemt_me_idle_close_by_peer_total 44131
telemt_me_route_drop_no_conn_total 186200
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439300
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1963
telemt_desync_full_logged_total 579
telemt_desync_suppressed_total 1384
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 758
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 43335
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 39403
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3922
telemt_user_connections_total{user="hello"} 458181
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 9848591723 (9.17 GB)
telemt_user_octets_to_client{user="hello"} 190500619784 (177.42 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 130126.5 (36h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215427
telemt_connections_bad_total 33267
telemt_handshake_timeouts_total 1925
telemt_upstream_connect_attempt_total 45967
telemt_upstream_connect_success_total 45521
telemt_upstream_connect_fail_total 446
telemt_upstream_connect_attempts_per_request{bucket="1"} 45967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 446
telemt_me_keepalive_timeout_total 2665
telemt_me_reconnect_attempts_total 50028
telemt_me_reconnect_success_total 34154
telemt_me_reader_eof_total 36538
telemt_me_idle_close_by_peer_total 36538
telemt_me_route_drop_no_conn_total 64799
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169531
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 749
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 567
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 34959
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34136
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 805
telemt_user_connections_total{user="hello"} 174292
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 2635180713 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 82388407647 (76.73 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 179911.2 (49h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1038844
telemt_connections_bad_total 36875
telemt_handshake_timeouts_total 26752
telemt_upstream_connect_attempt_total 37477
telemt_upstream_connect_success_total 37278
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 37477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 4837
telemt_me_reconnect_attempts_total 33083
telemt_me_reconnect_success_total 28398
telemt_me_reader_eof_total 30463
telemt_me_idle_close_by_peer_total 30460
telemt_me_route_drop_no_conn_total 487104
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 962608
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 798
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 536
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 28902
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28391
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 935225
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 17171345400 (15.99 GB)
telemt_user_octets_to_client{user="hello"} 466698434744 (434.65 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 72
```