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

# Server Metrics 2026-03-20 09:14:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 57439.8 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1319540
telemt_connections_bad_total 70846
telemt_connections_current 2021
telemt_connections_me_current 2021
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34219
telemt_upstream_connect_attempt_total 10991
telemt_upstream_connect_success_total 10877
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 10991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 6976
telemt_me_reconnect_success_total 6922
telemt_me_reader_eof_total 7323
telemt_me_idle_close_by_peer_total 7321
telemt_me_route_drop_no_conn_total 397516
telemt_me_route_drop_channel_closed_total 237
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1088855
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5674
telemt_desync_full_logged_total 2014
telemt_desync_suppressed_total 3660
telemt_desync_frames_bucket_total{bucket="1_2"} 1191
telemt_desync_frames_bucket_total{bucket="3_10"} 2203
telemt_desync_frames_bucket_total{bucket="gt_10"} 2280
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 128
telemt_me_writer_removed_unexpected_total 6995
telemt_me_writer_restored_same_endpoint_total 6909
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1088404
telemt_user_connections_current{user="hello"} 2021
telemt_user_octets_from_client{user="hello"} 39821765876 (37.09 GB)
telemt_user_octets_to_client{user="hello"} 370579279865 (345.13 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 682
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 73895.5 (20h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5581472
telemt_connections_bad_total 485287
telemt_connections_current 3831
telemt_connections_me_current 3831
telemt_handshake_timeouts_total 115637
telemt_upstream_connect_attempt_total 13571
telemt_upstream_connect_success_total 13278
telemt_upstream_connect_fail_total 293
telemt_upstream_connect_attempts_per_request{bucket="1"} 13571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 293
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12653
telemt_me_reconnect_success_total 8369
telemt_me_reader_eof_total 8957
telemt_me_idle_close_by_peer_total 8956
telemt_me_route_drop_no_conn_total 3512880
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4608812
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16888
telemt_desync_full_logged_total 5650
telemt_desync_suppressed_total 11238
telemt_desync_frames_bucket_total{bucket="1_2"} 3373
telemt_desync_frames_bucket_total{bucket="3_10"} 6609
telemt_desync_frames_bucket_total{bucket="gt_10"} 6906
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 2055
telemt_me_writer_close_signal_drop_total 122
telemt_me_writer_removed_unexpected_total 8625
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8314
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 4611132
telemt_user_connections_current{user="hello"} 3831
telemt_user_octets_from_client{user="hello"} 62020294358 (57.76 GB)
telemt_user_octets_to_client{user="hello"} 1521908147382 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1397
telemt_user_unique_ips_recent_window{user="hello"} 517
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 7237.8 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442465
telemt_connections_bad_total 40901
telemt_connections_current 2997
telemt_connections_me_current 2997
telemt_handshake_timeouts_total 5134
telemt_upstream_connect_attempt_total 1425
telemt_upstream_connect_success_total 1425
telemt_upstream_connect_attempts_per_request{bucket="1"} 1425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 993
telemt_me_reconnect_success_total 980
telemt_me_reader_eof_total 979
telemt_me_idle_close_by_peer_total 979
telemt_me_route_drop_no_conn_total 150668
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358564
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1602
telemt_desync_full_logged_total 521
telemt_desync_suppressed_total 1081
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 549
telemt_desync_frames_bucket_total{bucket="gt_10"} 750
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 969
telemt_me_writer_restored_same_endpoint_total 980
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 358803
telemt_user_connections_current{user="hello"} 2997
telemt_user_octets_from_client{user="hello"} 5835798636 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 142275692215 (132.50 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1114
telemt_user_unique_ips_recent_window{user="hello"} 411
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 73874.0 (20h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5064091
telemt_connections_bad_total 612117
telemt_connections_current 5957
telemt_connections_me_current 5957
telemt_handshake_timeouts_total 74771
telemt_upstream_connect_attempt_total 13212
telemt_upstream_connect_success_total 13102
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 13212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 8926
telemt_me_reconnect_success_total 7956
telemt_me_reader_eof_total 8342
telemt_me_idle_close_by_peer_total 8337
telemt_me_route_drop_no_conn_total 3084182
telemt_me_route_drop_channel_closed_total 318
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3671485
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12676
telemt_desync_full_logged_total 4057
telemt_desync_suppressed_total 8619
telemt_desync_frames_bucket_total{bucket="1_2"} 2979
telemt_desync_frames_bucket_total{bucket="3_10"} 4757
telemt_desync_frames_bucket_total{bucket="gt_10"} 4940
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 377
telemt_me_writer_removed_unexpected_total 8065
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7955
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 3677836
telemt_user_connections_current{user="hello"} 5957
telemt_user_octets_from_client{user="hello"} 56710339946 (52.82 GB)
telemt_user_octets_to_client{user="hello"} 1369583346120 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1777
telemt_user_unique_ips_recent_window{user="hello"} 706
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 73861.5 (20h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7021001
telemt_connections_bad_total 328064
telemt_connections_current 5399
telemt_connections_me_current 5399
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 94118
telemt_upstream_connect_attempt_total 83215
telemt_upstream_connect_success_total 71448
telemt_upstream_connect_fail_total 11767
telemt_upstream_connect_attempts_per_request{bucket="1"} 83215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11739
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11767
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11554
telemt_me_reconnect_success_total 8404
telemt_me_reader_eof_total 8762
telemt_me_idle_close_by_peer_total 8760
telemt_me_route_drop_no_conn_total 10406472
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6055971
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
telemt_desync_total 15152
telemt_desync_full_logged_total 4398
telemt_desync_suppressed_total 10754
telemt_desync_frames_bucket_total{bucket="1_2"} 3365
telemt_desync_frames_bucket_total{bucket="3_10"} 6079
telemt_desync_frames_bucket_total{bucket="gt_10"} 5708
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 844
telemt_me_writer_removed_unexpected_total 9256
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8400
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 852
telemt_user_connections_total{user="hello"} 6115397
telemt_user_connections_current{user="hello"} 5399
telemt_user_octets_from_client{user="hello"} 54338398611 (50.61 GB)
telemt_user_octets_to_client{user="hello"} 933369621433 (869.27 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1603
telemt_user_unique_ips_recent_window{user="hello"} 883
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 11444.6 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2545217
telemt_connections_bad_total 193973
telemt_connections_current 6432
telemt_connections_me_current 6432
telemt_handshake_timeouts_total 29616
telemt_upstream_connect_attempt_total 1957
telemt_upstream_connect_success_total 1945
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 1343
telemt_me_reconnect_success_total 1335
telemt_me_reader_eof_total 1368
telemt_me_idle_close_by_peer_total 1367
telemt_me_route_drop_no_conn_total 3941541
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2163488
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4658
telemt_desync_full_logged_total 1319
telemt_desync_suppressed_total 3339
telemt_desync_frames_bucket_total{bucket="1_2"} 845
telemt_desync_frames_bucket_total{bucket="3_10"} 1896
telemt_desync_frames_bucket_total{bucket="gt_10"} 1917
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 1346
telemt_me_writer_restored_same_endpoint_total 1305
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 2158259
telemt_user_connections_current{user="hello"} 6432
telemt_user_octets_from_client{user="hello"} 18041312284 (16.80 GB)
telemt_user_octets_to_client{user="hello"} 272855617676 (254.12 GB)
telemt_user_unique_ips_current{user="hello"} 1956
telemt_user_unique_ips_recent_window{user="hello"} 960
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 1021.4 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30674
telemt_connections_bad_total 10500
telemt_connections_current 667
telemt_connections_me_current 667
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 320
telemt_upstream_connect_attempt_total 1732
telemt_upstream_connect_success_total 1723
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 244
telemt_me_reconnect_success_total 241
telemt_me_reader_eof_total 183
telemt_me_idle_close_by_peer_total 183
telemt_me_route_drop_no_conn_total 7369
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17522
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 36
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_me_writer_close_signal_drop_total 20
telemt_me_writer_removed_unexpected_total 202
telemt_me_writer_restored_same_endpoint_total 239
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 19040
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 334953203 (319.44 MB)
telemt_user_octets_to_client{user="hello"} 2959258620 (2.76 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 73826.1 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3785616
telemt_connections_bad_total 243170
telemt_connections_current 5955
telemt_connections_me_current 5955
telemt_handshake_timeouts_total 79139
telemt_upstream_connect_attempt_total 12952
telemt_upstream_connect_success_total 12871
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 12952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9280
telemt_me_reconnect_success_total 9213
telemt_me_reader_eof_total 9736
telemt_me_idle_close_by_peer_total 9736
telemt_me_route_drop_no_conn_total 1357285
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3191458
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15239
telemt_desync_full_logged_total 5074
telemt_desync_suppressed_total 10165
telemt_desync_frames_bucket_total{bucket="1_2"} 3018
telemt_desync_frames_bucket_total{bucket="3_10"} 5533
telemt_desync_frames_bucket_total{bucket="gt_10"} 6688
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 9353
telemt_me_writer_restored_same_endpoint_total 9196
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 3189390
telemt_user_connections_current{user="hello"} 5955
telemt_user_octets_from_client{user="hello"} 65503133000 (61.00 GB)
telemt_user_octets_to_client{user="hello"} 1624827228004 (1.48 TB)
telemt_user_unique_ips_current{user="hello"} 1923
telemt_user_unique_ips_recent_window{user="hello"} 746
```