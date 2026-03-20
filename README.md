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

# Server Metrics 2026-03-20 05:54:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 45387.7 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 883799
telemt_connections_bad_total 56808
telemt_connections_current 1334
telemt_connections_me_current 1334
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 22420
telemt_upstream_connect_attempt_total 8849
telemt_upstream_connect_success_total 8747
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 8848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5417
telemt_me_reconnect_success_total 5372
telemt_me_reader_eof_total 5696
telemt_me_idle_close_by_peer_total 5695
telemt_me_route_drop_no_conn_total 246481
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711866
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3782
telemt_desync_full_logged_total 1360
telemt_desync_suppressed_total 2422
telemt_desync_frames_bucket_total{bucket="1_2"} 715
telemt_desync_frames_bucket_total{bucket="3_10"} 1489
telemt_desync_frames_bucket_total{bucket="gt_10"} 1578
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 47
telemt_me_writer_removed_unexpected_total 5430
telemt_me_writer_restored_same_endpoint_total 5359
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 713411
telemt_user_connections_current{user="hello"} 1334
telemt_user_octets_from_client{user="hello"} 33374503968 (31.08 GB)
telemt_user_octets_to_client{user="hello"} 249337049765 (232.21 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 61843.4 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3900008
telemt_connections_bad_total 347513
telemt_connections_current 4198
telemt_connections_me_current 4198
telemt_handshake_timeouts_total 93897
telemt_upstream_connect_attempt_total 11597
telemt_upstream_connect_success_total 11384
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 11597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11347
telemt_me_reconnect_success_total 7095
telemt_me_reader_eof_total 7594
telemt_me_idle_close_by_peer_total 7593
telemt_me_route_drop_no_conn_total 1734234
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3196003
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13041
telemt_desync_full_logged_total 4341
telemt_desync_suppressed_total 8700
telemt_desync_frames_bucket_total{bucket="1_2"} 2496
telemt_desync_frames_bucket_total{bucket="3_10"} 5078
telemt_desync_frames_bucket_total{bucket="gt_10"} 5467
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 58
telemt_me_writer_removed_unexpected_total 7315
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7040
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 3195711
telemt_user_connections_current{user="hello"} 4198
telemt_user_octets_from_client{user="hello"} 48000836666 (44.70 GB)
telemt_user_octets_to_client{user="hello"} 1214818576966 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1518
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 61821.7 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3516788
telemt_connections_bad_total 502538
telemt_connections_current 3132
telemt_connections_me_current 3132
telemt_handshake_timeouts_total 54354
telemt_upstream_connect_attempt_total 9983
telemt_upstream_connect_success_total 9913
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 9983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7795
telemt_me_reconnect_success_total 6850
telemt_me_reader_eof_total 7223
telemt_me_idle_close_by_peer_total 7222
telemt_me_route_drop_no_conn_total 2082377
telemt_me_route_drop_channel_closed_total 184
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2474487
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9074
telemt_desync_full_logged_total 2820
telemt_desync_suppressed_total 6254
telemt_desync_frames_bucket_total{bucket="1_2"} 2256
telemt_desync_frames_bucket_total{bucket="3_10"} 3457
telemt_desync_frames_bucket_total{bucket="gt_10"} 3361
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 80
telemt_me_writer_removed_unexpected_total 6927
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6849
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 2469532
telemt_user_connections_current{user="hello"} 3132
telemt_user_octets_from_client{user="hello"} 37299676124 (34.74 GB)
telemt_user_octets_to_client{user="hello"} 1010018826040 (940.65 GB)
telemt_user_unique_ips_current{user="hello"} 1123
telemt_user_unique_ips_recent_window{user="hello"} 423
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 61809.1 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3321547
telemt_connections_bad_total 246528
telemt_connections_current 3618
telemt_connections_me_current 3618
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 49748
telemt_upstream_connect_attempt_total 67380
telemt_upstream_connect_success_total 62667
telemt_upstream_connect_fail_total 4713
telemt_upstream_connect_attempts_per_request{bucket="1"} 67380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 711
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4713
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10169
telemt_me_reconnect_success_total 7197
telemt_me_reader_eof_total 7505
telemt_me_idle_close_by_peer_total 7504
telemt_me_route_drop_no_conn_total 2395995
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2702621
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9921
telemt_desync_full_logged_total 3140
telemt_desync_suppressed_total 6781
telemt_desync_frames_bucket_total{bucket="1_2"} 2357
telemt_desync_frames_bucket_total{bucket="3_10"} 3691
telemt_desync_frames_bucket_total{bucket="gt_10"} 3873
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 674
telemt_me_writer_removed_unexpected_total 7912
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7193
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 715
telemt_user_connections_total{user="hello"} 2753076
telemt_user_connections_current{user="hello"} 3618
telemt_user_octets_from_client{user="hello"} 41173406088 (38.35 GB)
telemt_user_octets_to_client{user="hello"} 792839357579 (738.39 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1153
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 115532.6 (32h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6974801
telemt_connections_bad_total 1213102
telemt_connections_current 3653
telemt_connections_me_current 3653
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 122488
telemt_upstream_connect_attempt_total 129945
telemt_upstream_connect_success_total 96641
telemt_upstream_connect_fail_total 33304
telemt_upstream_connect_attempts_per_request{bucket="1"} 129945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1438
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33304
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80252
telemt_me_reconnect_success_total 14572
telemt_me_reader_eof_total 15679
telemt_me_idle_close_by_peer_total 15665
telemt_me_route_drop_no_conn_total 3001725
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4932294
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
telemt_desync_total 21288
telemt_desync_full_logged_total 6784
telemt_desync_suppressed_total 14504
telemt_desync_frames_bucket_total{bucket="1_2"} 3788
telemt_desync_frames_bucket_total{bucket="3_10"} 8812
telemt_desync_frames_bucket_total{bucket="gt_10"} 8688
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 14905
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14547
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 5007027
telemt_user_connections_current{user="hello"} 3653
telemt_user_octets_from_client{user="hello"} 79397190476 (73.94 GB)
telemt_user_octets_to_client{user="hello"} 1990439272680 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1237
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 61772.5 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1751644
telemt_connections_bad_total 107532
telemt_connections_current 1120
telemt_connections_me_current 1120
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 15098
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
telemt_desync_total 1691
telemt_desync_full_logged_total 604
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 753
telemt_desync_frames_bucket_total{bucket="gt_10"} 665
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
telemt_user_connections_total{user="hello"} 1564794
telemt_user_connections_current{user="hello"} 1120
telemt_user_octets_from_client{user="hello"} 9459515443 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 146638054906 (136.57 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 61773.8 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2557050
telemt_connections_bad_total 158353
telemt_connections_current 3234
telemt_connections_me_current 3234
telemt_handshake_timeouts_total 45767
telemt_upstream_connect_attempt_total 11031
telemt_upstream_connect_success_total 10963
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7945
telemt_me_reconnect_success_total 7895
telemt_me_reader_eof_total 8343
telemt_me_idle_close_by_peer_total 8343
telemt_me_route_drop_no_conn_total 885500
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2141083
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10717
telemt_desync_full_logged_total 3520
telemt_desync_suppressed_total 7197
telemt_desync_frames_bucket_total{bucket="1_2"} 2087
telemt_desync_frames_bucket_total{bucket="3_10"} 3767
telemt_desync_frames_bucket_total{bucket="gt_10"} 4863
telemt_pool_swap_total 63
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 8003
telemt_me_writer_restored_same_endpoint_total 7878
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 2139818
telemt_user_connections_current{user="hello"} 3234
telemt_user_octets_from_client{user="hello"} 47003712740 (43.78 GB)
telemt_user_octets_to_client{user="hello"} 1130364026696 (1.03 TB)
telemt_user_unique_ips_current{user="hello"} 1094
telemt_user_unique_ips_recent_window{user="hello"} 407
```