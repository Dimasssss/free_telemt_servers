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

# Server Metrics 2026-03-20 07:22:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 50700.6 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1060788
telemt_connections_bad_total 63333
telemt_connections_current 1759
telemt_connections_me_current 1759
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 27330
telemt_upstream_connect_attempt_total 9840
telemt_upstream_connect_success_total 9731
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 9840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6136
telemt_me_reconnect_success_total 6090
telemt_me_reader_eof_total 6449
telemt_me_idle_close_by_peer_total 6448
telemt_me_route_drop_no_conn_total 306988
telemt_me_route_drop_channel_closed_total 136
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 870001
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4437
telemt_desync_full_logged_total 1600
telemt_desync_suppressed_total 2837
telemt_desync_frames_bucket_total{bucket="1_2"} 897
telemt_desync_frames_bucket_total{bucket="3_10"} 1715
telemt_desync_frames_bucket_total{bucket="gt_10"} 1825
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 68
telemt_me_writer_removed_unexpected_total 6156
telemt_me_writer_restored_same_endpoint_total 6077
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 869429
telemt_user_connections_current{user="hello"} 1759
telemt_user_octets_from_client{user="hello"} 35303366080 (32.88 GB)
telemt_user_octets_to_client{user="hello"} 299967072985 (279.37 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 595
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 67156.1 (18h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4932426
telemt_connections_bad_total 439524
telemt_connections_current 4887
telemt_connections_me_current 4887
telemt_handshake_timeouts_total 102750
telemt_upstream_connect_attempt_total 12508
telemt_upstream_connect_success_total 12251
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 12508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 11963
telemt_me_reconnect_success_total 7691
telemt_me_reader_eof_total 8229
telemt_me_idle_close_by_peer_total 8228
telemt_me_route_drop_no_conn_total 3059266
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4073071
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15166
telemt_desync_full_logged_total 4986
telemt_desync_suppressed_total 10180
telemt_desync_frames_bucket_total{bucket="1_2"} 3001
telemt_desync_frames_bucket_total{bucket="3_10"} 5916
telemt_desync_frames_bucket_total{bucket="gt_10"} 6249
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 107
telemt_me_writer_removed_unexpected_total 7932
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7636
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 4074914
telemt_user_connections_current{user="hello"} 4887
telemt_user_octets_from_client{user="hello"} 54399144174 (50.66 GB)
telemt_user_octets_to_client{user="hello"} 1352748918534 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1650
telemt_user_unique_ips_recent_window{user="hello"} 622
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 497.0 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5434
telemt_connections_bad_total 340
telemt_connections_current 588
telemt_connections_me_current 588
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 218
telemt_upstream_connect_success_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 76
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 104
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 61
telemt_me_route_drop_no_conn_total 1457
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4718
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 34
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_me_writer_close_signal_drop_total 19
telemt_me_writer_removed_unexpected_total 80
telemt_me_writer_restored_same_endpoint_total 101
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 4769
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 52496132 (50.06 MB)
telemt_user_octets_to_client{user="hello"} 1679374271 (1.56 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 67134.2 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4215709
telemt_connections_bad_total 541102
telemt_connections_current 4046
telemt_connections_me_current 4046
telemt_handshake_timeouts_total 64803
telemt_upstream_connect_attempt_total 12334
telemt_upstream_connect_success_total 12228
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3086
telemt_me_reconnect_attempts_total 8389
telemt_me_reconnect_success_total 7426
telemt_me_reader_eof_total 7769
telemt_me_idle_close_by_peer_total 7764
telemt_me_route_drop_no_conn_total 2775091
telemt_me_route_drop_channel_closed_total 262
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3030129
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10708
telemt_desync_full_logged_total 3354
telemt_desync_suppressed_total 7354
telemt_desync_frames_bucket_total{bucket="1_2"} 2562
telemt_desync_frames_bucket_total{bucket="3_10"} 4092
telemt_desync_frames_bucket_total{bucket="gt_10"} 4054
telemt_pool_swap_total 66
telemt_me_writer_close_signal_drop_total 317
telemt_me_writer_removed_unexpected_total 7522
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7425
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 3036503
telemt_user_connections_current{user="hello"} 4046
telemt_user_octets_from_client{user="hello"} 42212356002 (39.31 GB)
telemt_user_octets_to_client{user="hello"} 1135482736548 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1312
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 67121.9 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4735365
telemt_connections_bad_total 288490
telemt_connections_current 5039
telemt_connections_me_current 5039
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 66662
telemt_upstream_connect_attempt_total 68152
telemt_upstream_connect_success_total 63411
telemt_upstream_connect_fail_total 4741
telemt_upstream_connect_attempts_per_request{bucket="1"} 68152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9926
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4741
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 10664
telemt_me_reconnect_success_total 7676
telemt_me_reader_eof_total 8019
telemt_me_idle_close_by_peer_total 8018
telemt_me_route_drop_no_conn_total 5723734
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3986138
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13033
telemt_desync_full_logged_total 3771
telemt_desync_suppressed_total 9262
telemt_desync_frames_bucket_total{bucket="1_2"} 2919
telemt_desync_frames_bucket_total{bucket="3_10"} 5146
telemt_desync_frames_bucket_total{bucket="gt_10"} 4968
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 679
telemt_me_writer_removed_unexpected_total 8406
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7672
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 730
telemt_user_connections_total{user="hello"} 4037515
telemt_user_connections_current{user="hello"} 5039
telemt_user_octets_from_client{user="hello"} 46798929524 (43.58 GB)
telemt_user_octets_to_client{user="hello"} 854887433147 (796.18 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1473
telemt_user_unique_ips_recent_window{user="hello"} 880
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 4705.4 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 761210
telemt_connections_bad_total 70276
telemt_connections_current 5188
telemt_connections_me_current 5188
telemt_handshake_timeouts_total 13876
telemt_upstream_connect_attempt_total 764
telemt_upstream_connect_success_total 760
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 471
telemt_me_reconnect_success_total 468
telemt_me_reader_eof_total 454
telemt_me_idle_close_by_peer_total 454
telemt_me_route_drop_no_conn_total 949617
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631543
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 1235
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 698
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 464
telemt_me_writer_restored_same_endpoint_total 438
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 631518
telemt_user_connections_current{user="hello"} 5188
telemt_user_octets_from_client{user="hello"} 8529947824 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 118709587504 (110.56 GB)
telemt_user_unique_ips_current{user="hello"} 1631
telemt_user_unique_ips_recent_window{user="hello"} 714
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 4640.3 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75163
telemt_connections_bad_total 13172
telemt_connections_current 718
telemt_connections_me_current 718
telemt_handshake_timeouts_total 872
telemt_upstream_connect_attempt_total 886
telemt_upstream_connect_success_total 878
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 591
telemt_me_reconnect_success_total 587
telemt_me_reader_eof_total 594
telemt_me_idle_close_by_peer_total 594
telemt_me_route_drop_no_conn_total 39878
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72404
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 251
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 168
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 592
telemt_me_writer_restored_same_endpoint_total 579
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 57868
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 630017380 (600.83 MB)
telemt_user_octets_to_client{user="hello"} 22960650716 (21.38 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 67086.6 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2998030
telemt_connections_bad_total 189623
telemt_connections_current 4776
telemt_connections_me_current 4776
telemt_handshake_timeouts_total 55007
telemt_upstream_connect_attempt_total 11805
telemt_upstream_connect_success_total 11731
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 11805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8453
telemt_me_reconnect_success_total 8397
telemt_me_reader_eof_total 8877
telemt_me_idle_close_by_peer_total 8877
telemt_me_route_drop_no_conn_total 1022589
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2520372
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12486
telemt_desync_full_logged_total 4067
telemt_desync_suppressed_total 8419
telemt_desync_frames_bucket_total{bucket="1_2"} 2503
telemt_desync_frames_bucket_total{bucket="3_10"} 4407
telemt_desync_frames_bucket_total{bucket="gt_10"} 5576
telemt_pool_swap_total 69
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8515
telemt_me_writer_restored_same_endpoint_total 8380
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 2518462
telemt_user_connections_current{user="hello"} 4776
telemt_user_octets_from_client{user="hello"} 54113656200 (50.40 GB)
telemt_user_octets_to_client{user="hello"} 1317076504328 (1.20 TB)
telemt_user_unique_ips_current{user="hello"} 1523
telemt_user_unique_ips_recent_window{user="hello"} 603
```