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

# Server Metrics 2026-03-20 08:18:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 54071.7 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1181990
telemt_connections_bad_total 65240
telemt_connections_current 1965
telemt_connections_me_current 1965
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31410
telemt_upstream_connect_attempt_total 10350
telemt_upstream_connect_success_total 10237
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 10350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6488
telemt_me_reconnect_success_total 6438
telemt_me_reader_eof_total 6813
telemt_me_idle_close_by_peer_total 6811
telemt_me_route_drop_no_conn_total 344961
telemt_me_route_drop_channel_closed_total 170
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 975818
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4958
telemt_desync_full_logged_total 1775
telemt_desync_suppressed_total 3183
telemt_desync_frames_bucket_total{bucket="1_2"} 1011
telemt_desync_frames_bucket_total{bucket="3_10"} 1923
telemt_desync_frames_bucket_total{bucket="gt_10"} 2024
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 84
telemt_me_writer_removed_unexpected_total 6507
telemt_me_writer_restored_same_endpoint_total 6425
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 975349
telemt_user_connections_current{user="hello"} 1965
telemt_user_octets_from_client{user="hello"} 38081161488 (35.47 GB)
telemt_user_octets_to_client{user="hello"} 332608187497 (309.77 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 652
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 70527.0 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5216289
telemt_connections_bad_total 464137
telemt_connections_current 3982
telemt_connections_me_current 3982
telemt_handshake_timeouts_total 110233
telemt_upstream_connect_attempt_total 13050
telemt_upstream_connect_success_total 12778
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 13050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12318
telemt_me_reconnect_success_total 8039
telemt_me_reader_eof_total 8603
telemt_me_idle_close_by_peer_total 8602
telemt_me_route_drop_no_conn_total 3155750
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4304539
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16036
telemt_desync_full_logged_total 5304
telemt_desync_suppressed_total 10732
telemt_desync_frames_bucket_total{bucket="1_2"} 3197
telemt_desync_frames_bucket_total{bucket="3_10"} 6253
telemt_desync_frames_bucket_total{bucket="gt_10"} 6586
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 112
telemt_me_writer_removed_unexpected_total 8286
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7984
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 4306691
telemt_user_connections_current{user="hello"} 3982
telemt_user_octets_from_client{user="hello"} 57303091418 (53.37 GB)
telemt_user_octets_to_client{user="hello"} 1438014286954 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1366
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 3869.1 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196855
telemt_connections_bad_total 17832
telemt_connections_current 2549
telemt_connections_me_current 2549
telemt_handshake_timeouts_total 2032
telemt_upstream_connect_attempt_total 771
telemt_upstream_connect_success_total 771
telemt_upstream_connect_attempts_per_request{bucket="1"} 771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 483
telemt_me_reconnect_success_total 475
telemt_me_reader_eof_total 457
telemt_me_idle_close_by_peer_total 457
telemt_me_route_drop_no_conn_total 66598
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162845
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 713
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 455
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 458
telemt_me_writer_restored_same_endpoint_total 475
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 163087
telemt_user_connections_current{user="hello"} 2549
telemt_user_octets_from_client{user="hello"} 2921152460 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 63566099407 (59.20 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 981
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 70504.5 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4620057
telemt_connections_bad_total 563625
telemt_connections_current 5032
telemt_connections_me_current 5032
telemt_handshake_timeouts_total 68907
telemt_upstream_connect_attempt_total 12807
telemt_upstream_connect_success_total 12700
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 12807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3086
telemt_me_reconnect_attempts_total 8684
telemt_me_reconnect_success_total 7717
telemt_me_reader_eof_total 8084
telemt_me_idle_close_by_peer_total 8079
telemt_me_route_drop_no_conn_total 2899368
telemt_me_route_drop_channel_closed_total 286
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3331483
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11682
telemt_desync_full_logged_total 3707
telemt_desync_suppressed_total 7975
telemt_desync_frames_bucket_total{bucket="1_2"} 2767
telemt_desync_frames_bucket_total{bucket="3_10"} 4433
telemt_desync_frames_bucket_total{bucket="gt_10"} 4482
telemt_pool_swap_total 70
telemt_me_writer_close_signal_drop_total 340
telemt_me_writer_removed_unexpected_total 7819
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7716
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 3337837
telemt_user_connections_current{user="hello"} 5032
telemt_user_octets_from_client{user="hello"} 48559605358 (45.22 GB)
telemt_user_octets_to_client{user="hello"} 1247710760988 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1609
telemt_user_unique_ips_recent_window{user="hello"} 664
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 70492.9 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5872763
telemt_connections_bad_total 308394
telemt_connections_current 6717
telemt_connections_me_current 6717
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 80358
telemt_upstream_connect_attempt_total 82704
telemt_upstream_connect_success_total 70965
telemt_upstream_connect_fail_total 11739
telemt_upstream_connect_attempts_per_request{bucket="1"} 82704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11739
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 11208
telemt_me_reconnect_success_total 8082
telemt_me_reader_eof_total 8420
telemt_me_idle_close_by_peer_total 8418
telemt_me_route_drop_no_conn_total 7885565
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5006018
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
telemt_desync_total 14016
telemt_desync_full_logged_total 4045
telemt_desync_suppressed_total 9971
telemt_desync_frames_bucket_total{bucket="1_2"} 3139
telemt_desync_frames_bucket_total{bucket="3_10"} 5596
telemt_desync_frames_bucket_total{bucket="gt_10"} 5281
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 829
telemt_me_writer_removed_unexpected_total 8916
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8078
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 834
telemt_user_connections_total{user="hello"} 5065243
telemt_user_connections_current{user="hello"} 6717
telemt_user_octets_from_client{user="hello"} 50276361131 (46.82 GB)
telemt_user_octets_to_client{user="hello"} 892710840209 (831.40 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1598
telemt_user_unique_ips_recent_window{user="hello"} 978
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 8076.2 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1678061
telemt_connections_bad_total 121202
telemt_connections_current 6033
telemt_connections_me_current 6033
telemt_handshake_timeouts_total 21550
telemt_upstream_connect_attempt_total 1374
telemt_upstream_connect_success_total 1366
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 942
telemt_me_reconnect_success_total 939
telemt_me_reader_eof_total 940
telemt_me_idle_close_by_peer_total 940
telemt_me_route_drop_no_conn_total 2577576
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1428804
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3135
telemt_desync_full_logged_total 916
telemt_desync_suppressed_total 2219
telemt_desync_frames_bucket_total{bucket="1_2"} 596
telemt_desync_frames_bucket_total{bucket="3_10"} 1260
telemt_desync_frames_bucket_total{bucket="gt_10"} 1279
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 941
telemt_me_writer_restored_same_endpoint_total 909
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 1426066
telemt_user_connections_current{user="hello"} 6033
telemt_user_octets_from_client{user="hello"} 13632643816 (12.70 GB)
telemt_user_octets_to_client{user="hello"} 195231218916 (181.82 GB)
telemt_user_unique_ips_current{user="hello"} 1808
telemt_user_unique_ips_recent_window{user="hello"} 962
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 8011.3 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125409
telemt_connections_bad_total 15145
telemt_connections_current 657
telemt_connections_me_current 657
telemt_handshake_timeouts_total 1563
telemt_upstream_connect_attempt_total 1400
telemt_upstream_connect_success_total 1388
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 971
telemt_me_reconnect_success_total 965
telemt_me_reader_eof_total 1001
telemt_me_idle_close_by_peer_total 1001
telemt_me_route_drop_no_conn_total 65071
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118946
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 374
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 976
telemt_me_writer_restored_same_endpoint_total 957
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 101910
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 1469666368 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 40122894152 (37.37 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 70457.6 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3364900
telemt_connections_bad_total 221047
telemt_connections_current 5701
telemt_connections_me_current 5701
telemt_handshake_timeouts_total 63442
telemt_upstream_connect_attempt_total 12369
telemt_upstream_connect_success_total 12291
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 12369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8838
telemt_me_reconnect_success_total 8778
telemt_me_reader_eof_total 9285
telemt_me_idle_close_by_peer_total 9285
telemt_me_route_drop_no_conn_total 1152283
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2827046
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13839
telemt_desync_full_logged_total 4563
telemt_desync_suppressed_total 9276
telemt_desync_frames_bucket_total{bucket="1_2"} 2761
telemt_desync_frames_bucket_total{bucket="3_10"} 4946
telemt_desync_frames_bucket_total{bucket="gt_10"} 6132
telemt_pool_swap_total 72
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 8906
telemt_me_writer_restored_same_endpoint_total 8761
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 2825020
telemt_user_connections_current{user="hello"} 5701
telemt_user_octets_from_client{user="hello"} 59702102720 (55.60 GB)
telemt_user_octets_to_client{user="hello"} 1464749304192 (1.33 TB)
telemt_user_unique_ips_current{user="hello"} 1764
telemt_user_unique_ips_recent_window{user="hello"} 684
```