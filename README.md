# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 05:48:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 45082.7 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 875302
telemt_connections_bad_total 56574
telemt_connections_current 1292
telemt_connections_me_current 1292
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 21955
telemt_upstream_connect_attempt_total 8789
telemt_upstream_connect_success_total 8688
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 8789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5370
telemt_me_reconnect_success_total 5326
telemt_me_reader_eof_total 5643
telemt_me_idle_close_by_peer_total 5642
telemt_me_route_drop_no_conn_total 243921
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 704470
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3745
telemt_desync_full_logged_total 1348
telemt_desync_suppressed_total 2397
telemt_desync_frames_bucket_total{bucket="1_2"} 706
telemt_desync_frames_bucket_total{bucket="3_10"} 1477
telemt_desync_frames_bucket_total{bucket="gt_10"} 1562
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 47
telemt_me_writer_removed_unexpected_total 5381
telemt_me_writer_restored_same_endpoint_total 5313
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 706001
telemt_user_connections_current{user="hello"} 1292
telemt_user_octets_from_client{user="hello"} 33305243248 (31.02 GB)
telemt_user_octets_to_client{user="hello"} 246554568093 (229.62 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 506
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 61538.4 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3871211
telemt_connections_bad_total 346049
telemt_connections_current 4378
telemt_connections_me_current 4378
telemt_handshake_timeouts_total 92237
telemt_upstream_connect_attempt_total 11576
telemt_upstream_connect_success_total 11363
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 11576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11326
telemt_me_reconnect_success_total 7074
telemt_me_reader_eof_total 7573
telemt_me_idle_close_by_peer_total 7572
telemt_me_route_drop_no_conn_total 1724678
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3172246
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12924
telemt_desync_full_logged_total 4310
telemt_desync_suppressed_total 8614
telemt_desync_frames_bucket_total{bucket="1_2"} 2449
telemt_desync_frames_bucket_total{bucket="3_10"} 5044
telemt_desync_frames_bucket_total{bucket="gt_10"} 5431
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 58
telemt_me_writer_removed_unexpected_total 7294
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7019
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 3171956
telemt_user_connections_current{user="hello"} 4378
telemt_user_octets_from_client{user="hello"} 47679621430 (44.41 GB)
telemt_user_octets_to_client{user="hello"} 1206260258634 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1515
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 61516.4 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3495447
telemt_connections_bad_total 502138
telemt_connections_current 3168
telemt_connections_me_current 3168
telemt_handshake_timeouts_total 54040
telemt_upstream_connect_attempt_total 9968
telemt_upstream_connect_success_total 9898
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 9968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7780
telemt_me_reconnect_success_total 6836
telemt_me_reader_eof_total 7207
telemt_me_idle_close_by_peer_total 7206
telemt_me_route_drop_no_conn_total 2076376
telemt_me_route_drop_channel_closed_total 184
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2458979
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9040
telemt_desync_full_logged_total 2802
telemt_desync_suppressed_total 6238
telemt_desync_frames_bucket_total{bucket="1_2"} 2249
telemt_desync_frames_bucket_total{bucket="3_10"} 3442
telemt_desync_frames_bucket_total{bucket="gt_10"} 3349
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 80
telemt_me_writer_removed_unexpected_total 6911
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6835
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 2454025
telemt_user_connections_current{user="hello"} 3168
telemt_user_octets_from_client{user="hello"} 37055639876 (34.51 GB)
telemt_user_octets_to_client{user="hello"} 1004491663192 (935.51 GB)
telemt_user_unique_ips_current{user="hello"} 1116
telemt_user_unique_ips_recent_window{user="hello"} 380
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 61504.1 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3266041
telemt_connections_bad_total 244412
telemt_connections_current 3405
telemt_connections_me_current 3405
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 48452
telemt_upstream_connect_attempt_total 67352
telemt_upstream_connect_success_total 62640
telemt_upstream_connect_fail_total 4712
telemt_upstream_connect_attempts_per_request{bucket="1"} 67352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 711
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4712
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10141
telemt_me_reconnect_success_total 7171
telemt_me_reader_eof_total 7478
telemt_me_idle_close_by_peer_total 7477
telemt_me_route_drop_no_conn_total 2294377
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2653646
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9784
telemt_desync_full_logged_total 3112
telemt_desync_suppressed_total 6672
telemt_desync_frames_bucket_total{bucket="1_2"} 2323
telemt_desync_frames_bucket_total{bucket="3_10"} 3624
telemt_desync_frames_bucket_total{bucket="gt_10"} 3837
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 674
telemt_me_writer_removed_unexpected_total 7885
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7167
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 714
telemt_user_connections_total{user="hello"} 2704066
telemt_user_connections_current{user="hello"} 3405
telemt_user_octets_from_client{user="hello"} 40878543120 (38.07 GB)
telemt_user_octets_to_client{user="hello"} 788892301799 (734.71 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1096
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 115227.4 (32h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6949860
telemt_connections_bad_total 1209934
telemt_connections_current 3738
telemt_connections_me_current 3738
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 122243
telemt_upstream_connect_attempt_total 129864
telemt_upstream_connect_success_total 96561
telemt_upstream_connect_fail_total 33303
telemt_upstream_connect_attempts_per_request{bucket="1"} 129864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1438
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33303
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80212
telemt_me_reconnect_success_total 14532
telemt_me_reader_eof_total 15635
telemt_me_idle_close_by_peer_total 15621
telemt_me_route_drop_no_conn_total 2993609
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4913855
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 21229
telemt_desync_full_logged_total 6757
telemt_desync_suppressed_total 14472
telemt_desync_frames_bucket_total{bucket="1_2"} 3773
telemt_desync_frames_bucket_total{bucket="3_10"} 8786
telemt_desync_frames_bucket_total{bucket="gt_10"} 8670
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 14865
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14507
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 4988587
telemt_user_connections_current{user="hello"} 3738
telemt_user_octets_from_client{user="hello"} 79134316940 (73.70 GB)
telemt_user_octets_to_client{user="hello"} 1981768741028 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1228
telemt_user_unique_ips_recent_window{user="hello"} 435
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 61467.5 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1724923
telemt_connections_bad_total 107488
telemt_connections_current 745
telemt_connections_me_current 745
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14994
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 60
telemt_me_keepalive_timeout_total 560
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473703
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1681
telemt_desync_full_logged_total 603
telemt_desync_suppressed_total 1078
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 750
telemt_desync_frames_bucket_total{bucket="gt_10"} 659
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1538860
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 9399144831 (8.75 GB)
telemt_user_octets_to_client{user="hello"} 146637172854 (136.57 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 61468.8 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2535664
telemt_connections_bad_total 157494
telemt_connections_current 3243
telemt_connections_me_current 3243
telemt_handshake_timeouts_total 45495
telemt_upstream_connect_attempt_total 10998
telemt_upstream_connect_success_total 10930
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 10998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7912
telemt_me_reconnect_success_total 7862
telemt_me_reader_eof_total 8310
telemt_me_idle_close_by_peer_total 8310
telemt_me_route_drop_no_conn_total 880526
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2125416
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10670
telemt_desync_full_logged_total 3498
telemt_desync_suppressed_total 7172
telemt_desync_frames_bucket_total{bucket="1_2"} 2079
telemt_desync_frames_bucket_total{bucket="3_10"} 3748
telemt_desync_frames_bucket_total{bucket="gt_10"} 4843
telemt_pool_swap_total 63
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 7970
telemt_me_writer_restored_same_endpoint_total 7845
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 2124131
telemt_user_connections_current{user="hello"} 3243
telemt_user_octets_from_client{user="hello"} 46579173404 (43.38 GB)
telemt_user_octets_to_client{user="hello"} 1123142279080 (1.02 TB)
telemt_user_unique_ips_current{user="hello"} 1106
telemt_user_unique_ips_recent_window{user="hello"} 397
```