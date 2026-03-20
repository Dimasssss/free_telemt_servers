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

# Server Metrics 2026-03-20 07:48:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 52228.0 (14h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113389
telemt_connections_bad_total 64499
telemt_connections_current 1777
telemt_connections_me_current 1777
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 28825
telemt_upstream_connect_attempt_total 10032
telemt_upstream_connect_success_total 9923
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 10032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6281
telemt_me_reconnect_success_total 6234
telemt_me_reader_eof_total 6601
telemt_me_idle_close_by_peer_total 6600
telemt_me_route_drop_no_conn_total 322830
telemt_me_route_drop_channel_closed_total 152
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 915992
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4662
telemt_desync_full_logged_total 1676
telemt_desync_suppressed_total 2986
telemt_desync_frames_bucket_total{bucket="1_2"} 941
telemt_desync_frames_bucket_total{bucket="3_10"} 1804
telemt_desync_frames_bucket_total{bucket="gt_10"} 1917
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 76
telemt_me_writer_removed_unexpected_total 6304
telemt_me_writer_restored_same_endpoint_total 6221
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 915445
telemt_user_connections_current{user="hello"} 1777
telemt_user_octets_from_client{user="hello"} 36484338248 (33.98 GB)
telemt_user_octets_to_client{user="hello"} 314705119405 (293.09 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 606
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 68683.4 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5060745
telemt_connections_bad_total 448073
telemt_connections_current 3601
telemt_connections_me_current 3601
telemt_handshake_timeouts_total 107588
telemt_upstream_connect_attempt_total 12765
telemt_upstream_connect_success_total 12500
telemt_upstream_connect_fail_total 265
telemt_upstream_connect_attempts_per_request{bucket="1"} 12765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 265
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12126
telemt_me_reconnect_success_total 7850
telemt_me_reader_eof_total 8401
telemt_me_idle_close_by_peer_total 8400
telemt_me_route_drop_no_conn_total 3100693
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4179137
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15476
telemt_desync_full_logged_total 5112
telemt_desync_suppressed_total 10364
telemt_desync_frames_bucket_total{bucket="1_2"} 3042
telemt_desync_frames_bucket_total{bucket="3_10"} 6036
telemt_desync_frames_bucket_total{bucket="gt_10"} 6398
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 109
telemt_me_writer_removed_unexpected_total 8095
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7795
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 4181134
telemt_user_connections_current{user="hello"} 3601
telemt_user_octets_from_client{user="hello"} 55763563670 (51.93 GB)
telemt_user_octets_to_client{user="hello"} 1390950394026 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1282
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 2025.2 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77011
telemt_connections_bad_total 5318
telemt_connections_current 2099
telemt_connections_me_current 2099
telemt_handshake_timeouts_total 688
telemt_upstream_connect_attempt_total 480
telemt_upstream_connect_success_total 480
telemt_upstream_connect_attempts_per_request{bucket="1"} 480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 279
telemt_me_reconnect_success_total 275
telemt_me_reader_eof_total 245
telemt_me_idle_close_by_peer_total 245
telemt_me_route_drop_no_conn_total 26794
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67448
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 251
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 255
telemt_me_writer_restored_same_endpoint_total 275
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 67515
telemt_user_connections_current{user="hello"} 2099
telemt_user_octets_from_client{user="hello"} 1524910776 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 24404724655 (22.73 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 807
telemt_user_unique_ips_recent_window{user="hello"} 335
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 68661.1 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4388721
telemt_connections_bad_total 552097
telemt_connections_current 4623
telemt_connections_me_current 4623
telemt_handshake_timeouts_total 66431
telemt_upstream_connect_attempt_total 12559
telemt_upstream_connect_success_total 12453
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3086
telemt_me_reconnect_attempts_total 8525
telemt_me_reconnect_success_total 7561
telemt_me_reader_eof_total 7915
telemt_me_idle_close_by_peer_total 7910
telemt_me_route_drop_no_conn_total 2827891
telemt_me_route_drop_channel_closed_total 271
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3160914
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11190
telemt_desync_full_logged_total 3519
telemt_desync_suppressed_total 7671
telemt_desync_frames_bucket_total{bucket="1_2"} 2668
telemt_desync_frames_bucket_total{bucket="3_10"} 4256
telemt_desync_frames_bucket_total{bucket="gt_10"} 4266
telemt_pool_swap_total 68
telemt_me_writer_close_signal_drop_total 323
telemt_me_writer_removed_unexpected_total 7660
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7560
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 3167281
telemt_user_connections_current{user="hello"} 4623
telemt_user_octets_from_client{user="hello"} 44111548958 (41.08 GB)
telemt_user_octets_to_client{user="hello"} 1185214211288 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1476
telemt_user_unique_ips_recent_window{user="hello"} 579
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 68649.9 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5209482
telemt_connections_bad_total 298202
telemt_connections_current 4684
telemt_connections_me_current 4684
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 72371
telemt_upstream_connect_attempt_total 82436
telemt_upstream_connect_success_total 70711
telemt_upstream_connect_fail_total 11725
telemt_upstream_connect_attempts_per_request{bucket="1"} 82436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11389
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11725
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 131
telemt_me_reconnect_attempts_total 11029
telemt_me_reconnect_success_total 7915
telemt_me_reader_eof_total 8240
telemt_me_idle_close_by_peer_total 8239
telemt_me_route_drop_no_conn_total 6546852
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4398829
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
telemt_desync_total 13487
telemt_desync_full_logged_total 3886
telemt_desync_suppressed_total 9601
telemt_desync_frames_bucket_total{bucket="1_2"} 3010
telemt_desync_frames_bucket_total{bucket="3_10"} 5364
telemt_desync_frames_bucket_total{bucket="gt_10"} 5113
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 824
telemt_me_writer_removed_unexpected_total 8738
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7911
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 823
telemt_user_connections_total{user="hello"} 4458082
telemt_user_connections_current{user="hello"} 4684
telemt_user_octets_from_client{user="hello"} 48314605647 (45.00 GB)
telemt_user_octets_to_client{user="hello"} 870905745201 (811.09 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1398
telemt_user_unique_ips_recent_window{user="hello"} 812
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 6232.3 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1167200
telemt_connections_bad_total 95291
telemt_connections_current 5628
telemt_connections_me_current 5628
telemt_handshake_timeouts_total 17661
telemt_upstream_connect_attempt_total 979
telemt_upstream_connect_success_total 975
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 643
telemt_me_reconnect_success_total 641
telemt_me_reader_eof_total 636
telemt_me_idle_close_by_peer_total 636
telemt_me_route_drop_no_conn_total 1689445
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 985354
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2323
telemt_desync_full_logged_total 695
telemt_desync_suppressed_total 1628
telemt_desync_frames_bucket_total{bucket="1_2"} 458
telemt_desync_frames_bucket_total{bucket="3_10"} 951
telemt_desync_frames_bucket_total{bucket="gt_10"} 914
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 27
telemt_me_writer_removed_unexpected_total 637
telemt_me_writer_restored_same_endpoint_total 611
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 985295
telemt_user_connections_current{user="hello"} 5628
telemt_user_octets_from_client{user="hello"} 10801141012 (10.06 GB)
telemt_user_octets_to_client{user="hello"} 154311287960 (143.71 GB)
telemt_user_unique_ips_current{user="hello"} 1710
telemt_user_unique_ips_recent_window{user="hello"} 1056
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 6167.6 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96673
telemt_connections_bad_total 13863
telemt_connections_current 681
telemt_connections_me_current 681
telemt_handshake_timeouts_total 1025
telemt_upstream_connect_attempt_total 1108
telemt_upstream_connect_success_total 1099
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 769
telemt_me_reconnect_success_total 764
telemt_me_reader_eof_total 780
telemt_me_idle_close_by_peer_total 780
telemt_me_route_drop_no_conn_total 49552
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93169
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 287
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 770
telemt_me_writer_restored_same_endpoint_total 756
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 77534
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 1205237792 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 31166242272 (29.03 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 68614.1 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3159219
telemt_connections_bad_total 210420
telemt_connections_current 5284
telemt_connections_me_current 5284
telemt_handshake_timeouts_total 57538
telemt_upstream_connect_attempt_total 12025
telemt_upstream_connect_success_total 11950
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 12025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8585
telemt_me_reconnect_success_total 8529
telemt_me_reader_eof_total 9020
telemt_me_idle_close_by_peer_total 9020
telemt_me_route_drop_no_conn_total 1074424
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2650030
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13037
telemt_desync_full_logged_total 4242
telemt_desync_suppressed_total 8795
telemt_desync_frames_bucket_total{bucket="1_2"} 2594
telemt_desync_frames_bucket_total{bucket="3_10"} 4650
telemt_desync_frames_bucket_total{bucket="gt_10"} 5793
telemt_pool_swap_total 71
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8651
telemt_me_writer_restored_same_endpoint_total 8512
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 2647926
telemt_user_connections_current{user="hello"} 5284
telemt_user_octets_from_client{user="hello"} 56047234380 (52.20 GB)
telemt_user_octets_to_client{user="hello"} 1383494767308 (1.26 TB)
telemt_user_unique_ips_current{user="hello"} 1641
telemt_user_unique_ips_recent_window{user="hello"} 658
```