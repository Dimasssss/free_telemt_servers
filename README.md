# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

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
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

# Server Metrics 2026-03-20 08:28:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 54680.9 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205132
telemt_connections_bad_total 65930
telemt_connections_current 1808
telemt_connections_me_current 1808
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32105
telemt_upstream_connect_attempt_total 10525
telemt_upstream_connect_success_total 10412
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 10525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6640
telemt_me_reconnect_success_total 6589
telemt_me_reader_eof_total 6963
telemt_me_idle_close_by_peer_total 6961
telemt_me_route_drop_no_conn_total 352374
telemt_me_route_drop_channel_closed_total 177
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 995332
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5037
telemt_desync_full_logged_total 1811
telemt_desync_suppressed_total 3226
telemt_desync_frames_bucket_total{bucket="1_2"} 1032
telemt_desync_frames_bucket_total{bucket="3_10"} 1955
telemt_desync_frames_bucket_total{bucket="gt_10"} 2050
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 90
telemt_me_writer_removed_unexpected_total 6658
telemt_me_writer_restored_same_endpoint_total 6576
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 994883
telemt_user_connections_current{user="hello"} 1808
telemt_user_octets_from_client{user="hello"} 38269944600 (35.64 GB)
telemt_user_octets_to_client{user="hello"} 339502369337 (316.19 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 71136.4 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5269845
telemt_connections_bad_total 467375
telemt_connections_current 3900
telemt_connections_me_current 3900
telemt_handshake_timeouts_total 111162
telemt_upstream_connect_attempt_total 13085
telemt_upstream_connect_success_total 12813
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 13085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12346
telemt_me_reconnect_success_total 8067
telemt_me_reader_eof_total 8633
telemt_me_idle_close_by_peer_total 8632
telemt_me_route_drop_no_conn_total 3174117
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4348659
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16203
telemt_desync_full_logged_total 5367
telemt_desync_suppressed_total 10836
telemt_desync_frames_bucket_total{bucket="1_2"} 3243
telemt_desync_frames_bucket_total{bucket="3_10"} 6309
telemt_desync_frames_bucket_total{bucket="gt_10"} 6651
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 114
telemt_me_writer_removed_unexpected_total 8316
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8012
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 4350816
telemt_user_connections_current{user="hello"} 3900
telemt_user_octets_from_client{user="hello"} 58273654394 (54.27 GB)
telemt_user_octets_to_client{user="hello"} 1453109928874 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1389
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 4478.5 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241956
telemt_connections_bad_total 20223
telemt_connections_current 2637
telemt_connections_me_current 2637
telemt_handshake_timeouts_total 2577
telemt_upstream_connect_attempt_total 810
telemt_upstream_connect_success_total 810
telemt_upstream_connect_attempts_per_request{bucket="1"} 810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 522
telemt_me_reconnect_success_total 513
telemt_me_reader_eof_total 496
telemt_me_idle_close_by_peer_total 496
telemt_me_route_drop_no_conn_total 79994
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195601
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 902
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 592
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 498
telemt_me_writer_restored_same_endpoint_total 513
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 195854
telemt_user_connections_current{user="hello"} 2637
telemt_user_octets_from_client{user="hello"} 3252224324 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 77288497867 (71.98 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 995
telemt_user_unique_ips_recent_window{user="hello"} 369
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 71115.0 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4697517
telemt_connections_bad_total 567854
telemt_connections_current 5166
telemt_connections_me_current 5166
telemt_handshake_timeouts_total 69870
telemt_upstream_connect_attempt_total 12841
telemt_upstream_connect_success_total 12734
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 12841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3094
telemt_me_reconnect_attempts_total 8718
telemt_me_reconnect_success_total 7751
telemt_me_reader_eof_total 8120
telemt_me_idle_close_by_peer_total 8115
telemt_me_route_drop_no_conn_total 2923177
telemt_me_route_drop_channel_closed_total 292
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3386598
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11843
telemt_desync_full_logged_total 3766
telemt_desync_suppressed_total 8077
telemt_desync_frames_bucket_total{bucket="1_2"} 2795
telemt_desync_frames_bucket_total{bucket="3_10"} 4489
telemt_desync_frames_bucket_total{bucket="gt_10"} 4559
telemt_pool_swap_total 70
telemt_me_writer_close_signal_drop_total 345
telemt_me_writer_removed_unexpected_total 7855
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7750
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 3392950
telemt_user_connections_current{user="hello"} 5166
telemt_user_octets_from_client{user="hello"} 49480016458 (46.08 GB)
telemt_user_octets_to_client{user="hello"} 1270464366332 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1628
telemt_user_unique_ips_recent_window{user="hello"} 671
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 71102.2 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6114873
telemt_connections_bad_total 311612
telemt_connections_current 5276
telemt_connections_me_current 5276
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 83108
telemt_upstream_connect_attempt_total 82731
telemt_upstream_connect_success_total 70990
telemt_upstream_connect_fail_total 11741
telemt_upstream_connect_attempts_per_request{bucket="1"} 82731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11741
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11235
telemt_me_reconnect_success_total 8107
telemt_me_reader_eof_total 8445
telemt_me_idle_close_by_peer_total 8443
telemt_me_route_drop_no_conn_total 8427585
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5229890
telemt_me_writer_pick_total{mode="p2c",result="full"} 4273
telemt_me_writer_pick_total{mode="p2c",result="closed"} 804
telemt_me_writer_pick_blocking_fallback_total 5052
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14273
telemt_desync_full_logged_total 4111
telemt_desync_suppressed_total 10162
telemt_desync_frames_bucket_total{bucket="1_2"} 3206
telemt_desync_frames_bucket_total{bucket="3_10"} 5697
telemt_desync_frames_bucket_total{bucket="gt_10"} 5370
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 830
telemt_me_writer_removed_unexpected_total 8942
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8103
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 835
telemt_user_connections_total{user="hello"} 5289158
telemt_user_connections_current{user="hello"} 5276
telemt_user_octets_from_client{user="hello"} 50822210795 (47.33 GB)
telemt_user_octets_to_client{user="hello"} 899512884661 (837.74 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1561
telemt_user_unique_ips_recent_window{user="hello"} 934
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 8685.4 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1844852
telemt_connections_bad_total 130465
telemt_connections_current 6260
telemt_connections_me_current 6260
telemt_handshake_timeouts_total 23116
telemt_upstream_connect_attempt_total 1488
telemt_upstream_connect_success_total 1479
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 1012
telemt_me_reconnect_success_total 1009
telemt_me_reader_eof_total 1024
telemt_me_idle_close_by_peer_total 1024
telemt_me_route_drop_no_conn_total 2891979
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1568898
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3380
telemt_desync_full_logged_total 985
telemt_desync_suppressed_total 2395
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 1382
telemt_desync_frames_bucket_total{bucket="gt_10"} 1366
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 1012
telemt_me_writer_restored_same_endpoint_total 979
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 1564767
telemt_user_connections_current{user="hello"} 6260
telemt_user_octets_from_client{user="hello"} 14500564348 (13.50 GB)
telemt_user_octets_to_client{user="hello"} 207708212356 (193.44 GB)
telemt_user_unique_ips_current{user="hello"} 1863
telemt_user_unique_ips_recent_window{user="hello"} 884
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 8621.0 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134042
telemt_connections_bad_total 16063
telemt_connections_current 700
telemt_connections_me_current 700
telemt_handshake_timeouts_total 1628
telemt_upstream_connect_attempt_total 1526
telemt_upstream_connect_success_total 1513
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1053
telemt_me_reconnect_success_total 1045
telemt_me_reader_eof_total 1089
telemt_me_idle_close_by_peer_total 1089
telemt_me_route_drop_no_conn_total 68982
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126255
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 413
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 277
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 1058
telemt_me_writer_restored_same_endpoint_total 1037
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 109219
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 1593462008 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 43352006580 (40.37 GB)
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 71067.0 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3433107
telemt_connections_bad_total 224003
telemt_connections_current 5778
telemt_connections_me_current 5778
telemt_handshake_timeouts_total 67107
telemt_upstream_connect_attempt_total 12402
telemt_upstream_connect_success_total 12324
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 12402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8871
telemt_me_reconnect_success_total 8811
telemt_me_reader_eof_total 9320
telemt_me_idle_close_by_peer_total 9320
telemt_me_route_drop_no_conn_total 1177320
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2885479
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14131
telemt_desync_full_logged_total 4691
telemt_desync_suppressed_total 9440
telemt_desync_frames_bucket_total{bucket="1_2"} 2794
telemt_desync_frames_bucket_total{bucket="3_10"} 5082
telemt_desync_frames_bucket_total{bucket="gt_10"} 6255
telemt_pool_swap_total 72
telemt_me_writer_close_signal_drop_total 52
telemt_me_writer_removed_unexpected_total 8941
telemt_me_writer_restored_same_endpoint_total 8794
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 2883453
telemt_user_connections_current{user="hello"} 5778
telemt_user_octets_from_client{user="hello"} 61319924776 (57.11 GB)
telemt_user_octets_to_client{user="hello"} 1494827432436 (1.36 TB)
telemt_user_unique_ips_current{user="hello"} 1817
telemt_user_unique_ips_recent_window{user="hello"} 693
```