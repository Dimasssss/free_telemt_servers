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

# Server Metrics 2026-03-19 14:45:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 1012.1 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57249
telemt_connections_bad_total 23
telemt_connections_current 74
telemt_connections_direct_current 74
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 172
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 50137
telemt_upstream_connect_attempt_total 2728
telemt_upstream_connect_success_total 2728
telemt_upstream_connect_attempts_per_request{bucket="1"} 2728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2726
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 12609663 (12.03 MB)
telemt_user_octets_to_client{user="hello"} 1011707272 (964.84 MB)
telemt_user_msgs_from_client{user="hello"} 27380
telemt_user_msgs_to_client{user="hello"} 57244
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 7326.9 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 783038
telemt_connections_bad_total 26688
telemt_connections_current 4118
telemt_connections_me_current 4118
telemt_handshake_timeouts_total 15955
telemt_upstream_connect_attempt_total 2744
telemt_upstream_connect_success_total 2721
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 5273
telemt_me_reconnect_success_total 1059
telemt_me_reader_eof_total 1153
telemt_me_idle_close_by_peer_total 1153
telemt_me_route_drop_no_conn_total 607062
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 674465
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2417
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1651
telemt_desync_frames_bucket_total{bucket="1_2"} 436
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 1045
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 1178
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1004
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 675254
telemt_user_connections_current{user="hello"} 4118
telemt_user_octets_from_client{user="hello"} 8417492810 (7.84 GB)
telemt_user_octets_to_client{user="hello"} 179553802878 (167.22 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1400
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 7292.7 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624947
telemt_connections_bad_total 42362
telemt_connections_current 2991
telemt_connections_me_current 2991
telemt_handshake_timeouts_total 9800
telemt_upstream_connect_attempt_total 10218
telemt_upstream_connect_success_total 9725
telemt_upstream_connect_fail_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 10218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 493
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1070
telemt_me_reconnect_success_total 862
telemt_me_reader_eof_total 832
telemt_me_idle_close_by_peer_total 831
telemt_me_route_drop_no_conn_total 422570
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516723
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2244
telemt_desync_full_logged_total 736
telemt_desync_suppressed_total 1508
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 923
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 76
telemt_me_writer_removed_unexpected_total 971
telemt_me_writer_restored_same_endpoint_total 858
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 524708
telemt_user_connections_current{user="hello"} 2991
telemt_user_octets_from_client{user="hello"} 9606944079 (8.95 GB)
telemt_user_octets_to_client{user="hello"} 116699301040 (108.68 GB)
telemt_user_msgs_from_client{user="hello"} 16739
telemt_user_msgs_to_client{user="hello"} 18599
telemt_user_unique_ips_current{user="hello"} 1020
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 61015.8 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4253778
telemt_connections_bad_total 793193
telemt_connections_current 3476
telemt_connections_me_current 3476
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 82332
telemt_upstream_connect_attempt_total 62731
telemt_upstream_connect_success_total 60247
telemt_upstream_connect_fail_total 2484
telemt_upstream_connect_attempts_per_request{bucket="1"} 62731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1022
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2484
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 73411
telemt_me_reconnect_success_total 8014
telemt_me_reader_eof_total 8440
telemt_me_idle_close_by_peer_total 8437
telemt_me_route_drop_no_conn_total 2017389
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2918858
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
telemt_desync_total 12622
telemt_desync_full_logged_total 3890
telemt_desync_suppressed_total 8732
telemt_desync_frames_bucket_total{bucket="1_2"} 2157
telemt_desync_frames_bucket_total{bucket="3_10"} 5410
telemt_desync_frames_bucket_total{bucket="gt_10"} 5055
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8225
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 7990
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 2967502
telemt_user_connections_current{user="hello"} 3476
telemt_user_octets_from_client{user="hello"} 47337550203 (44.09 GB)
telemt_user_octets_to_client{user="hello"} 1054538284372 (982.12 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1144
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 7257.7 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167581
telemt_connections_bad_total 8923
telemt_connections_current 1042
telemt_connections_me_current 1042
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 5131
telemt_upstream_connect_attempt_total 4068
telemt_upstream_connect_success_total 3931
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1015
telemt_me_reconnect_success_total 991
telemt_me_reader_eof_total 958
telemt_me_idle_close_by_peer_total 958
telemt_me_route_drop_no_conn_total 112096
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142602
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 412
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 283
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 962
telemt_me_writer_restored_same_endpoint_total 982
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 145224
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 2121809720 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 36129840058 (33.65 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 7257.0 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497512
telemt_connections_bad_total 34556
telemt_connections_current 3109
telemt_connections_me_current 3109
telemt_handshake_timeouts_total 9312
telemt_upstream_connect_attempt_total 1148
telemt_upstream_connect_success_total 1140
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 751
telemt_me_reconnect_success_total 738
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 761
telemt_me_route_drop_no_conn_total 175165
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428552
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2310
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 1616
telemt_desync_frames_bucket_total{bucket="1_2"} 448
telemt_desync_frames_bucket_total{bucket="3_10"} 762
telemt_desync_frames_bucket_total{bucket="gt_10"} 1100
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 762
telemt_me_writer_restored_same_endpoint_total 721
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 428279
telemt_user_connections_current{user="hello"} 3109
telemt_user_octets_from_client{user="hello"} 5894318060 (5.49 GB)
telemt_user_octets_to_client{user="hello"} 180822943992 (168.40 GB)
telemt_user_unique_ips_current{user="hello"} 1027
telemt_user_unique_ips_recent_window{user="hello"} 456
```