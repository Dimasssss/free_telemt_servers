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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 08:14:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 658.0 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30867
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 192
telemt_upstream_connect_attempt_total 2846
telemt_upstream_connect_success_total 2751
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 2846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 38
telemt_me_reconnect_success_total 30
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 11776
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23230
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 27
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 29
telemt_me_writer_restored_same_endpoint_total 28
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 547
telemt_user_connections_total{user="hello"} 25882
telemt_user_connections_current{user="hello"} 785
telemt_user_octets_from_client{user="hello"} 386966835 (369.04 MB)
telemt_user_octets_to_client{user="hello"} 3708163253 (3.45 GB)
telemt_user_msgs_from_client{user="hello"} 11108
telemt_user_msgs_to_client{user="hello"} 12747
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 135205.1 (37h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2061022
telemt_connections_bad_total 109504
telemt_handshake_timeouts_total 62832
telemt_upstream_connect_attempt_total 472696
telemt_upstream_connect_success_total 471038
telemt_upstream_connect_fail_total 1658
telemt_upstream_connect_attempts_per_request{bucket="1"} 472696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1658
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 135976
telemt_me_reconnect_success_total 21368
telemt_me_reader_eof_total 23927
telemt_me_idle_close_by_peer_total 23913
telemt_me_route_drop_no_conn_total 674381
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1352780
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6092
telemt_desync_full_logged_total 2115
telemt_desync_suppressed_total 3977
telemt_desync_frames_bucket_total{bucket="1_2"} 1150
telemt_desync_frames_bucket_total{bucket="3_10"} 2470
telemt_desync_frames_bucket_total{bucket="gt_10"} 2472
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 23254
telemt_me_refill_failed_total 3575
telemt_me_writer_restored_same_endpoint_total 21350
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1886
telemt_user_connections_total{user="hello"} 1795164
telemt_user_connections_current{user="hello"} 3225
telemt_user_octets_from_client{user="hello"} 30547915849 (28.45 GB)
telemt_user_octets_to_client{user="hello"} 705840839018 (657.37 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 969
telemt_user_unique_ips_recent_window{user="hello"} 412
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 134981.4 (37h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1557454
telemt_connections_bad_total 94714
telemt_handshake_timeouts_total 35862
telemt_upstream_connect_attempt_total 30439
telemt_upstream_connect_success_total 30270
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 30439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 45086
telemt_me_reconnect_success_total 23486
telemt_me_reader_eof_total 25513
telemt_me_idle_close_by_peer_total 25505
telemt_me_route_drop_no_conn_total 672775
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1145172
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4100
telemt_desync_full_logged_total 1391
telemt_desync_suppressed_total 2709
telemt_desync_frames_bucket_total{bucket="1_2"} 1117
telemt_desync_frames_bucket_total{bucket="3_10"} 1581
telemt_desync_frames_bucket_total{bucket="gt_10"} 1402
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24498
telemt_me_refill_failed_total 669
telemt_me_writer_restored_same_endpoint_total 23474
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 1012
telemt_user_connections_total{user="hello"} 1143132
telemt_user_connections_current{user="hello"} 2033
telemt_user_octets_from_client{user="hello"} 51051361760 (47.55 GB)
telemt_user_octets_to_client{user="hello"} 528330928384 (492.05 GB)
telemt_user_unique_ips_current{user="hello"} 596
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 135040.3 (37h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2013619
telemt_connections_bad_total 90140
telemt_handshake_timeouts_total 38722
telemt_upstream_connect_attempt_total 93572
telemt_upstream_connect_success_total 91106
telemt_upstream_connect_fail_total 2466
telemt_upstream_connect_attempts_per_request{bucket="1"} 93572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 388
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2466
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 41135
telemt_me_reconnect_success_total 19597
telemt_me_reader_eof_total 21458
telemt_me_idle_close_by_peer_total 21455
telemt_me_route_drop_no_conn_total 1043578
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1680626
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6539
telemt_desync_full_logged_total 2003
telemt_desync_suppressed_total 4536
telemt_desync_frames_bucket_total{bucket="1_2"} 1464
telemt_desync_frames_bucket_total{bucket="3_10"} 2691
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20635
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19577
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1038
telemt_user_connections_total{user="hello"} 1743674
telemt_user_connections_current{user="hello"} 2839
telemt_user_octets_from_client{user="hello"} 27432900322 (25.55 GB)
telemt_user_octets_to_client{user="hello"} 750370363282 (698.84 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 793
telemt_user_unique_ips_recent_window{user="hello"} 375
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 135012.2 (37h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1461220
telemt_connections_bad_total 121929
telemt_handshake_timeouts_total 17625
telemt_upstream_connect_attempt_total 50123
telemt_upstream_connect_success_total 49424
telemt_upstream_connect_fail_total 699
telemt_upstream_connect_attempts_per_request{bucket="1"} 50123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 699
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 69125
telemt_me_reconnect_success_total 26245
telemt_me_reader_eof_total 28571
telemt_me_idle_close_by_peer_total 28568
telemt_me_route_drop_no_conn_total 625547
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1215279
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5235
telemt_desync_full_logged_total 1619
telemt_desync_suppressed_total 3616
telemt_desync_frames_bucket_total{bucket="1_2"} 1317
telemt_desync_frames_bucket_total{bucket="3_10"} 2028
telemt_desync_frames_bucket_total{bucket="gt_10"} 1890
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27990
telemt_me_refill_failed_total 1334
telemt_me_writer_restored_same_endpoint_total 26237
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1745
telemt_user_connections_total{user="hello"} 1231525
telemt_user_connections_current{user="hello"} 2663
telemt_user_octets_from_client{user="hello"} 23872155900 (22.23 GB)
telemt_user_octets_to_client{user="hello"} 587079118364 (546.76 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 781
telemt_user_unique_ips_recent_window{user="hello"} 367
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 135173.6 (37h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1361669
telemt_connections_bad_total 142925
telemt_handshake_timeouts_total 11214
telemt_upstream_connect_attempt_total 27020
telemt_upstream_connect_success_total 26861
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 292
telemt_me_reconnect_attempts_total 31434
telemt_me_reconnect_success_total 20119
telemt_me_reader_eof_total 21756
telemt_me_idle_close_by_peer_total 21753
telemt_me_route_drop_no_conn_total 932862
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1317355
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2581
telemt_desync_full_logged_total 907
telemt_desync_suppressed_total 1674
telemt_desync_frames_bucket_total{bucket="1_2"} 554
telemt_desync_frames_bucket_total{bucket="3_10"} 1002
telemt_desync_frames_bucket_total{bucket="gt_10"} 1025
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20781
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 20105
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 662
telemt_user_connections_total{user="hello"} 1126016
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 17080418556 (15.91 GB)
telemt_user_octets_to_client{user="hello"} 477322591088 (444.54 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 82940.5 (23h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 835949
telemt_connections_bad_total 78262
telemt_handshake_timeouts_total 17767
telemt_upstream_connect_attempt_total 27535
telemt_upstream_connect_success_total 27218
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 27535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 37179
telemt_me_reconnect_success_total 22914
telemt_me_reader_eof_total 24242
telemt_me_idle_close_by_peer_total 24242
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 265226
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 635702
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2544
telemt_desync_full_logged_total 870
telemt_desync_suppressed_total 1674
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 1035
telemt_desync_frames_bucket_total{bucket="gt_10"} 1068
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23614
telemt_me_refill_failed_total 441
telemt_me_writer_restored_same_endpoint_total 22867
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 700
telemt_user_connections_total{user="hello"} 635347
telemt_user_connections_current{user="hello"} 1975
telemt_user_octets_from_client{user="hello"} 30355193489 (28.27 GB)
telemt_user_octets_to_client{user="hello"} 445337845974 (414.75 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 259
```