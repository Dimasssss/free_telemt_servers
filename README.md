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

# Server Metrics 2026-03-14 09:40:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 180428.4 (50h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 699235
telemt_connections_bad_total 32677
telemt_handshake_timeouts_total 13632
telemt_upstream_connect_attempt_total 45827
telemt_upstream_connect_success_total 45594
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 45827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5901
telemt_me_reconnect_attempts_total 40925
telemt_me_reconnect_success_total 36223
telemt_me_reader_eof_total 38730
telemt_me_idle_close_by_peer_total 38729
telemt_me_route_drop_no_conn_total 230890
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598257
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2376
telemt_desync_full_logged_total 791
telemt_desync_suppressed_total 1585
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 875
telemt_desync_frames_bucket_total{bucket="gt_10"} 995
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 36757
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 36203
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 598135
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 17255806574 (16.07 GB)
telemt_user_octets_to_client{user="hello"} 286596901412 (266.91 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 180321.4 (50h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351569
telemt_connections_bad_total 2809
telemt_handshake_timeouts_total 3067
telemt_upstream_connect_attempt_total 153409
telemt_upstream_connect_success_total 152063
telemt_upstream_connect_fail_total 1346
telemt_upstream_connect_attempts_per_request{bucket="1"} 153409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1346
telemt_me_keepalive_timeout_total 5404
telemt_me_reconnect_attempts_total 186708
telemt_me_reconnect_success_total 39767
telemt_me_reader_eof_total 45410
telemt_me_idle_close_by_peer_total 45410
telemt_me_route_drop_no_conn_total 119888
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228686
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 44737
telemt_me_refill_failed_total 4585
telemt_me_writer_restored_same_endpoint_total 39750
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4970
telemt_user_connections_total{user="hello"} 331790
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 3421181143 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 106319716359 (99.02 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 180284.8 (50h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408080
telemt_connections_bad_total 3212
telemt_handshake_timeouts_total 35652
telemt_upstream_connect_attempt_total 47821
telemt_upstream_connect_success_total 47812
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3713
telemt_me_reconnect_attempts_total 40075
telemt_me_reconnect_success_total 38775
telemt_me_reader_eof_total 41681
telemt_me_idle_close_by_peer_total 41681
telemt_me_route_drop_no_conn_total 148142
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 354833
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
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 39241
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38754
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 354559
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 13755663428 (12.81 GB)
telemt_user_octets_to_client{user="hello"} 156600239212 (145.85 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 180260.6 (50h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515078
telemt_connections_bad_total 16708
telemt_handshake_timeouts_total 5104
telemt_upstream_connect_attempt_total 78201
telemt_upstream_connect_success_total 67541
telemt_upstream_connect_fail_total 10660
telemt_upstream_connect_attempts_per_request{bucket="1"} 78201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10660
telemt_me_keepalive_timeout_total 5557
telemt_me_reconnect_attempts_total 151809
telemt_me_reconnect_success_total 39516
telemt_me_reader_eof_total 44278
telemt_me_idle_close_by_peer_total 44270
telemt_me_route_drop_no_conn_total 186501
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440132
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
telemt_me_writer_removed_unexpected_total 43474
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 39506
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3958
telemt_user_connections_total{user="hello"} 459013
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 9858695531 (9.18 GB)
telemt_user_octets_to_client{user="hello"} 190723344248 (177.62 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 130432.0 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216147
telemt_connections_bad_total 33322
telemt_handshake_timeouts_total 1928
telemt_upstream_connect_attempt_total 46055
telemt_upstream_connect_success_total 45609
telemt_upstream_connect_fail_total 446
telemt_upstream_connect_attempts_per_request{bucket="1"} 46055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 446
telemt_me_keepalive_timeout_total 2672
telemt_me_reconnect_attempts_total 50116
telemt_me_reconnect_success_total 34241
telemt_me_reader_eof_total 36626
telemt_me_idle_close_by_peer_total 36626
telemt_me_route_drop_no_conn_total 65020
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170182
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 752
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 358
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 35047
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34223
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 806
telemt_user_connections_total{user="hello"} 174941
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 2638627849 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 82594944659 (76.92 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 180216.7 (50h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1041132
telemt_connections_bad_total 36890
telemt_handshake_timeouts_total 26766
telemt_upstream_connect_attempt_total 37588
telemt_upstream_connect_success_total 37388
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 37588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 4844
telemt_me_reconnect_attempts_total 33145
telemt_me_reconnect_success_total 28459
telemt_me_reader_eof_total 30525
telemt_me_idle_close_by_peer_total 30522
telemt_me_route_drop_no_conn_total 487924
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 964724
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
telemt_me_writer_removed_unexpected_total 28964
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28452
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 505
telemt_user_connections_total{user="hello"} 937341
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 17214636680 (16.03 GB)
telemt_user_octets_to_client{user="hello"} 468070124984 (435.92 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 69
```