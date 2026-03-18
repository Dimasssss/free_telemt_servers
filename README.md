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

# Server Metrics 2026-03-18 08:39:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 2184.7 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96712
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 1169
telemt_upstream_connect_attempt_total 22509
telemt_upstream_connect_success_total 21818
telemt_upstream_connect_fail_total 691
telemt_upstream_connect_attempts_per_request{bucket="1"} 22509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 691
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 317634
telemt_me_reconnect_success_total 563
telemt_me_reader_eof_total 467
telemt_me_idle_close_by_peer_total 467
telemt_me_route_drop_no_conn_total 29439
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63938
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 29
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 245
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 158
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 488
telemt_me_refill_failed_total 9906
telemt_me_writer_restored_same_endpoint_total 560
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 14752
telemt_user_connections_total{user="hello"} 85007
telemt_user_connections_current{user="hello"} 1250
telemt_user_octets_from_client{user="hello"} 881126041 (840.31 MB)
telemt_user_octets_to_client{user="hello"} 13815261323 (12.87 GB)
telemt_user_msgs_from_client{user="hello"} 186832
telemt_user_msgs_to_client{user="hello"} 242060
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 405
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 136732.4 (37h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2163191
telemt_connections_bad_total 117620
telemt_handshake_timeouts_total 64113
telemt_upstream_connect_attempt_total 472923
telemt_upstream_connect_success_total 471259
telemt_upstream_connect_fail_total 1664
telemt_upstream_connect_attempts_per_request{bucket="1"} 472923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1664
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 137624
telemt_me_reconnect_success_total 21541
telemt_me_reader_eof_total 24150
telemt_me_idle_close_by_peer_total 24136
telemt_me_route_drop_no_conn_total 732847
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1442187
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6392
telemt_desync_full_logged_total 2216
telemt_desync_suppressed_total 4176
telemt_desync_frames_bucket_total{bucket="1_2"} 1206
telemt_desync_frames_bucket_total{bucket="3_10"} 2573
telemt_desync_frames_bucket_total{bucket="gt_10"} 2613
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 23476
telemt_me_refill_failed_total 3621
telemt_me_writer_restored_same_endpoint_total 21523
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1935
telemt_user_connections_total{user="hello"} 1884547
telemt_user_connections_current{user="hello"} 3159
telemt_user_octets_from_client{user="hello"} 32157578001 (29.95 GB)
telemt_user_octets_to_client{user="hello"} 745104031462 (693.93 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 1001
telemt_user_unique_ips_recent_window{user="hello"} 420
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 136508.9 (37h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1645866
telemt_connections_bad_total 98894
telemt_handshake_timeouts_total 36953
telemt_upstream_connect_attempt_total 30651
telemt_upstream_connect_success_total 30480
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 30651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 47864
telemt_me_reconnect_success_total 23607
telemt_me_reader_eof_total 25717
telemt_me_idle_close_by_peer_total 25709
telemt_me_route_drop_no_conn_total 721411
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 17
telemt_me_route_drop_queue_full_profile_total{profile="high"} 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1215121
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4426
telemt_desync_full_logged_total 1505
telemt_desync_suppressed_total 2921
telemt_desync_frames_bucket_total{bucket="1_2"} 1202
telemt_desync_frames_bucket_total{bucket="3_10"} 1703
telemt_desync_frames_bucket_total{bucket="gt_10"} 1521
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24702
telemt_me_refill_failed_total 752
telemt_me_writer_restored_same_endpoint_total 23595
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 1095
telemt_user_connections_total{user="hello"} 1213049
telemt_user_connections_current{user="hello"} 2223
telemt_user_octets_from_client{user="hello"} 52276740744 (48.69 GB)
telemt_user_octets_to_client{user="hello"} 547528717744 (509.93 GB)
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 323
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 136568.0 (37h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2122837
telemt_connections_bad_total 96292
telemt_handshake_timeouts_total 40620
telemt_upstream_connect_attempt_total 93855
telemt_upstream_connect_success_total 91388
telemt_upstream_connect_fail_total 2467
telemt_upstream_connect_attempts_per_request{bucket="1"} 93855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 389
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2467
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 42268
telemt_me_reconnect_success_total 19802
telemt_me_reader_eof_total 21709
telemt_me_idle_close_by_peer_total 21706
telemt_me_route_drop_no_conn_total 1114614
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1774836
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6876
telemt_desync_full_logged_total 2090
telemt_desync_suppressed_total 4786
telemt_desync_frames_bucket_total{bucket="1_2"} 1521
telemt_desync_frames_bucket_total{bucket="3_10"} 2823
telemt_desync_frames_bucket_total{bucket="gt_10"} 2532
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 20876
telemt_me_refill_failed_total 692
telemt_me_writer_restored_same_endpoint_total 19782
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1074
telemt_user_connections_total{user="hello"} 1837890
telemt_user_connections_current{user="hello"} 2974
telemt_user_octets_from_client{user="hello"} 29761680990 (27.72 GB)
telemt_user_octets_to_client{user="hello"} 774216351966 (721.05 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 377
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 136539.6 (37h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1548286
telemt_connections_bad_total 130796
telemt_handshake_timeouts_total 19445
telemt_upstream_connect_attempt_total 50289
telemt_upstream_connect_success_total 49579
telemt_upstream_connect_fail_total 710
telemt_upstream_connect_attempts_per_request{bucket="1"} 50289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 434
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 710
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 71945
telemt_me_reconnect_success_total 26313
telemt_me_reader_eof_total 28724
telemt_me_idle_close_by_peer_total 28721
telemt_me_route_drop_no_conn_total 662732
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1285747
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5558
telemt_desync_full_logged_total 1708
telemt_desync_suppressed_total 3850
telemt_desync_frames_bucket_total{bucket="1_2"} 1386
telemt_desync_frames_bucket_total{bucket="3_10"} 2132
telemt_desync_frames_bucket_total{bucket="gt_10"} 2040
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 28144
telemt_me_refill_failed_total 1420
telemt_me_writer_restored_same_endpoint_total 26305
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1831
telemt_user_connections_total{user="hello"} 1301959
telemt_user_connections_current{user="hello"} 2535
telemt_user_octets_from_client{user="hello"} 24763691572 (23.06 GB)
telemt_user_octets_to_client{user="hello"} 613177952480 (571.07 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 762
telemt_user_unique_ips_recent_window{user="hello"} 350
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 136700.9 (37h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1387876
telemt_connections_bad_total 147074
telemt_handshake_timeouts_total 11354
telemt_upstream_connect_attempt_total 27272
telemt_upstream_connect_success_total 27111
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 27272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 293
telemt_me_reconnect_attempts_total 31640
telemt_me_reconnect_success_total 20323
telemt_me_reader_eof_total 21965
telemt_me_idle_close_by_peer_total 21962
telemt_me_route_drop_no_conn_total 943729
telemt_me_route_drop_channel_closed_total 103
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1338593
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2633
telemt_desync_full_logged_total 924
telemt_desync_suppressed_total 1709
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 1049
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20990
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 20309
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 667
telemt_user_connections_total{user="hello"} 1147233
telemt_user_connections_current{user="hello"} 905
telemt_user_octets_from_client{user="hello"} 17328616876 (16.14 GB)
telemt_user_octets_to_client{user="hello"} 481876097932 (448.78 GB)
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 84468.0 (23h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 894145
telemt_connections_bad_total 81922
telemt_handshake_timeouts_total 18457
telemt_upstream_connect_attempt_total 27721
telemt_upstream_connect_success_total 27397
telemt_upstream_connect_fail_total 324
telemt_upstream_connect_attempts_per_request{bucket="1"} 27721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 324
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 38344
telemt_me_reconnect_success_total 23048
telemt_me_reader_eof_total 24399
telemt_me_idle_close_by_peer_total 24399
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 290469
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 686521
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2674
telemt_desync_full_logged_total 918
telemt_desync_suppressed_total 1756
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 1086
telemt_desync_frames_bucket_total{bucket="gt_10"} 1132
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23781
telemt_me_refill_failed_total 473
telemt_me_writer_restored_same_endpoint_total 23001
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 733
telemt_user_connections_total{user="hello"} 686127
telemt_user_connections_current{user="hello"} 1919
telemt_user_octets_from_client{user="hello"} 31126811749 (28.99 GB)
telemt_user_octets_to_client{user="hello"} 468944200314 (436.74 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 596
telemt_user_unique_ips_recent_window{user="hello"} 261
```