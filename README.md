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

# Server Metrics 2026-03-19 21:59:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 16936.3 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398136
telemt_connections_bad_total 20307
telemt_connections_current 789
telemt_connections_me_current 789
telemt_handshake_timeouts_total 5790
telemt_upstream_connect_attempt_total 2771
telemt_upstream_connect_success_total 2747
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1906
telemt_me_reconnect_success_total 1892
telemt_me_reader_eof_total 2000
telemt_me_idle_close_by_peer_total 2000
telemt_me_route_drop_no_conn_total 120990
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316683
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1724
telemt_desync_full_logged_total 597
telemt_desync_suppressed_total 1127
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 540
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1934
telemt_me_writer_restored_same_endpoint_total 1879
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 316953
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 11177249976 (10.41 GB)
telemt_user_octets_to_client{user="hello"} 118077680284 (109.97 GB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 33391.8 (9h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2738411
telemt_connections_bad_total 117394
telemt_connections_current 1864
telemt_connections_me_current 1864
telemt_handshake_timeouts_total 54049
telemt_upstream_connect_attempt_total 6821
telemt_upstream_connect_success_total 6713
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 6821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8020
telemt_me_reconnect_success_total 3790
telemt_me_reader_eof_total 4070
telemt_me_idle_close_by_peer_total 4070
telemt_me_route_drop_no_conn_total 1429240
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2336546
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10362
telemt_desync_full_logged_total 3373
telemt_desync_suppressed_total 6989
telemt_desync_frames_bucket_total{bucket="1_2"} 1927
telemt_desync_frames_bucket_total{bucket="3_10"} 4041
telemt_desync_frames_bucket_total{bucket="gt_10"} 4394
telemt_pool_swap_total 25
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 3958
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3735
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 2336423
telemt_user_connections_current{user="hello"} 1864
telemt_user_octets_from_client{user="hello"} 37046178446 (34.50 GB)
telemt_user_octets_to_client{user="hello"} 832874872998 (775.68 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 779
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 33370.0 (9h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2665942
telemt_connections_bad_total 457331
telemt_connections_current 1377
telemt_connections_me_current 1377
telemt_handshake_timeouts_total 33619
telemt_upstream_connect_attempt_total 5206
telemt_upstream_connect_success_total 5164
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 5206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4397
telemt_me_reconnect_success_total 3471
telemt_me_reader_eof_total 3605
telemt_me_idle_close_by_peer_total 3604
telemt_me_route_drop_no_conn_total 1853751
telemt_me_route_drop_channel_closed_total 166
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1863971
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7237
telemt_desync_full_logged_total 2174
telemt_desync_suppressed_total 5063
telemt_desync_frames_bucket_total{bucket="1_2"} 1800
telemt_desync_frames_bucket_total{bucket="3_10"} 2762
telemt_desync_frames_bucket_total{bucket="gt_10"} 2675
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 60
telemt_me_writer_removed_unexpected_total 3493
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3470
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1859909
telemt_user_connections_current{user="hello"} 1377
telemt_user_octets_from_client{user="hello"} 28211552808 (26.27 GB)
telemt_user_octets_to_client{user="hello"} 682145067340 (635.30 GB)
telemt_user_unique_ips_current{user="hello"} 575
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 33357.6 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2336590
telemt_connections_bad_total 97555
telemt_connections_current 1432
telemt_connections_me_current 1432
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29279
telemt_upstream_connect_attempt_total 35438
telemt_upstream_connect_success_total 33708
telemt_upstream_connect_fail_total 1730
telemt_upstream_connect_attempts_per_request{bucket="1"} 35438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 450
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1730
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6567
telemt_me_reconnect_success_total 3950
telemt_me_reader_eof_total 4088
telemt_me_idle_close_by_peer_total 4087
telemt_me_route_drop_no_conn_total 1816211
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1987699
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7981
telemt_desync_full_logged_total 2493
telemt_desync_suppressed_total 5488
telemt_desync_frames_bucket_total{bucket="1_2"} 1959
telemt_desync_frames_bucket_total{bucket="3_10"} 2901
telemt_desync_frames_bucket_total{bucket="gt_10"} 3121
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 348
telemt_me_writer_removed_unexpected_total 4464
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3946
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 2014632
telemt_user_connections_current{user="hello"} 1432
telemt_user_octets_from_client{user="hello"} 33158283264 (30.88 GB)
telemt_user_octets_to_client{user="hello"} 517443034151 (481.91 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 87080.8 (24h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6006987
telemt_connections_bad_total 1032612
telemt_connections_current 1681
telemt_connections_me_current 1681
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 108754
telemt_upstream_connect_attempt_total 66801
telemt_upstream_connect_success_total 64295
telemt_upstream_connect_fail_total 2506
telemt_upstream_connect_attempts_per_request{bucket="1"} 66801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2506
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76196
telemt_me_reconnect_success_total 10778
telemt_me_reader_eof_total 11378
telemt_me_idle_close_by_peer_total 11375
telemt_me_route_drop_no_conn_total 2737563
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4263142
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
telemt_desync_total 18788
telemt_desync_full_logged_total 5835
telemt_desync_suppressed_total 12953
telemt_desync_frames_bucket_total{bucket="1_2"} 3272
telemt_desync_frames_bucket_total{bucket="3_10"} 7729
telemt_desync_frames_bucket_total{bucket="gt_10"} 7787
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 11042
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10754
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 4311192
telemt_user_connections_current{user="hello"} 1681
telemt_user_octets_from_client{user="hello"} 66841706095 (62.25 GB)
telemt_user_octets_to_client{user="hello"} 1665038008440 (1.51 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 652
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 33320.9 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 623773
telemt_connections_bad_total 49150
telemt_connections_current 402
telemt_connections_me_current 402
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11936
telemt_upstream_connect_attempt_total 9266
telemt_upstream_connect_success_total 9053
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 9266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 564
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4477
telemt_me_reconnect_success_total 4398
telemt_me_reader_eof_total 4576
telemt_me_idle_close_by_peer_total 4574
telemt_me_route_drop_no_conn_total 428979
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516503
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
telemt_desync_total 1353
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 847
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 26
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 144
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4437
telemt_me_writer_restored_same_endpoint_total 4389
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 515994
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 6804467548 (6.34 GB)
telemt_user_octets_to_client{user="hello"} 120183933430 (111.93 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 33322.2 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1849906
telemt_connections_bad_total 108403
telemt_connections_current 1612
telemt_connections_me_current 1612
telemt_handshake_timeouts_total 33687
telemt_upstream_connect_attempt_total 5540
telemt_upstream_connect_success_total 5499
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 5540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3859
telemt_me_reconnect_success_total 3823
telemt_me_reader_eof_total 4023
telemt_me_idle_close_by_peer_total 4023
telemt_me_route_drop_no_conn_total 691785
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1603650
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8604
telemt_desync_full_logged_total 2704
telemt_desync_suppressed_total 5900
telemt_desync_frames_bucket_total{bucket="1_2"} 1580
telemt_desync_frames_bucket_total{bucket="3_10"} 3002
telemt_desync_frames_bucket_total{bucket="gt_10"} 4022
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 3894
telemt_me_writer_restored_same_endpoint_total 3806
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1602797
telemt_user_connections_current{user="hello"} 1612
telemt_user_octets_from_client{user="hello"} 27408268812 (25.53 GB)
telemt_user_octets_to_client{user="hello"} 799986840184 (745.05 GB)
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 138
```