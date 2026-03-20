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

# Server Metrics 2026-03-20 09:40:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 58964.5 (16h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1391219
telemt_connections_bad_total 73265
telemt_connections_current 1912
telemt_connections_me_current 1912
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 35615
telemt_upstream_connect_attempt_total 11255
telemt_upstream_connect_success_total 11136
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 11255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 7147
telemt_me_reconnect_success_total 7092
telemt_me_reader_eof_total 7505
telemt_me_idle_close_by_peer_total 7503
telemt_me_route_drop_no_conn_total 417193
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1141903
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6100
telemt_desync_full_logged_total 2144
telemt_desync_suppressed_total 3956
telemt_desync_frames_bucket_total{bucket="1_2"} 1319
telemt_desync_frames_bucket_total{bucket="3_10"} 2343
telemt_desync_frames_bucket_total{bucket="gt_10"} 2438
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 137
telemt_me_writer_removed_unexpected_total 7170
telemt_me_writer_restored_same_endpoint_total 7079
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1141580
telemt_user_connections_current{user="hello"} 1912
telemt_user_octets_from_client{user="hello"} 40973481444 (38.16 GB)
telemt_user_octets_to_client{user="hello"} 386864530769 (360.30 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 673
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 75420.7 (20h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5738449
telemt_connections_bad_total 509579
telemt_connections_current 4054
telemt_connections_me_current 4054
telemt_handshake_timeouts_total 118133
telemt_upstream_connect_attempt_total 13894
telemt_upstream_connect_success_total 13598
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 13894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12920
telemt_me_reconnect_success_total 8635
telemt_me_reader_eof_total 9224
telemt_me_idle_close_by_peer_total 9223
telemt_me_route_drop_no_conn_total 3565603
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4721114
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17380
telemt_desync_full_logged_total 5833
telemt_desync_suppressed_total 11547
telemt_desync_frames_bucket_total{bucket="1_2"} 3486
telemt_desync_frames_bucket_total{bucket="3_10"} 6819
telemt_desync_frames_bucket_total{bucket="gt_10"} 7075
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3394
telemt_me_writer_close_signal_drop_total 127
telemt_me_writer_removed_unexpected_total 8893
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8580
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 4723095
telemt_user_connections_current{user="hello"} 4054
telemt_user_octets_from_client{user="hello"} 63910556986 (59.52 GB)
telemt_user_octets_to_client{user="hello"} 1560323296342 (1.42 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1421
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 8762.9 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568816
telemt_connections_bad_total 53487
telemt_connections_current 3219
telemt_connections_me_current 3219
telemt_handshake_timeouts_total 6298
telemt_upstream_connect_attempt_total 1644
telemt_upstream_connect_success_total 1644
telemt_upstream_connect_attempts_per_request{bucket="1"} 1644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1137
telemt_me_reconnect_success_total 1124
telemt_me_reader_eof_total 1136
telemt_me_idle_close_by_peer_total 1136
telemt_me_route_drop_no_conn_total 205652
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 459727
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1942
telemt_desync_full_logged_total 633
telemt_desync_suppressed_total 1309
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 884
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 1118
telemt_me_writer_restored_same_endpoint_total 1124
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 459991
telemt_user_connections_current{user="hello"} 3219
telemt_user_octets_from_client{user="hello"} 7277175968 (6.78 GB)
telemt_user_octets_to_client{user="hello"} 178943609663 (166.65 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1241
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 75386.4 (20h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7620218
telemt_connections_bad_total 338561
telemt_connections_current 5576
telemt_connections_me_current 5576
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 100082
telemt_upstream_connect_attempt_total 83427
telemt_upstream_connect_success_total 71648
telemt_upstream_connect_fail_total 11779
telemt_upstream_connect_attempts_per_request{bucket="1"} 83427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11779
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 11696
telemt_me_reconnect_success_total 8539
telemt_me_reader_eof_total 8911
telemt_me_idle_close_by_peer_total 8909
telemt_me_route_drop_no_conn_total 11930351
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6603285
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
telemt_desync_total 15765
telemt_desync_full_logged_total 4587
telemt_desync_suppressed_total 11178
telemt_desync_frames_bucket_total{bucket="1_2"} 3488
telemt_desync_frames_bucket_total{bucket="3_10"} 6330
telemt_desync_frames_bucket_total{bucket="gt_10"} 5947
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 847
telemt_me_writer_removed_unexpected_total 9396
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8535
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 857
telemt_user_connections_total{user="hello"} 6662682
telemt_user_connections_current{user="hello"} 5576
telemt_user_octets_from_client{user="hello"} 56566632331 (52.68 GB)
telemt_user_octets_to_client{user="hello"} 949619087437 (884.40 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1692
telemt_user_unique_ips_recent_window{user="hello"} 988
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 12969.6 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2889754
telemt_connections_bad_total 241277
telemt_connections_current 6330
telemt_connections_me_current 6330
telemt_handshake_timeouts_total 33192
telemt_upstream_connect_attempt_total 2182
telemt_upstream_connect_success_total 2169
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 1480
telemt_me_reconnect_success_total 1472
telemt_me_reader_eof_total 1518
telemt_me_idle_close_by_peer_total 1517
telemt_me_route_drop_no_conn_total 4434502
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2434735
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5276
telemt_desync_full_logged_total 1514
telemt_desync_suppressed_total 3762
telemt_desync_frames_bucket_total{bucket="1_2"} 970
telemt_desync_frames_bucket_total{bucket="3_10"} 2141
telemt_desync_frames_bucket_total{bucket="gt_10"} 2165
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 1486
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 2429514
telemt_user_connections_current{user="hello"} 6330
telemt_user_octets_from_client{user="hello"} 20926181548 (19.49 GB)
telemt_user_octets_to_client{user="hello"} 308611694224 (287.42 GB)
telemt_user_unique_ips_current{user="hello"} 1975
telemt_user_unique_ips_recent_window{user="hello"} 943
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 2547.9 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58647
telemt_connections_bad_total 13219
telemt_connections_current 860
telemt_connections_me_current 860
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 1275
telemt_upstream_connect_attempt_total 1960
telemt_upstream_connect_success_total 1949
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 425
telemt_me_reconnect_success_total 421
telemt_me_reader_eof_total 380
telemt_me_idle_close_by_peer_total 380
telemt_me_route_drop_no_conn_total 17632
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40728
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 21
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_restored_same_endpoint_total 419
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 42248
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 745870039 (711.32 MB)
telemt_user_octets_to_client{user="hello"} 7000913552 (6.52 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 75351.1 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3973953
telemt_connections_bad_total 250986
telemt_connections_current 6439
telemt_connections_me_current 6439
telemt_handshake_timeouts_total 86692
telemt_upstream_connect_attempt_total 13167
telemt_upstream_connect_success_total 13083
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 13167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9408
telemt_me_reconnect_success_total 9341
telemt_me_reader_eof_total 9885
telemt_me_idle_close_by_peer_total 9884
telemt_me_route_drop_no_conn_total 1425020
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3353182
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16032
telemt_desync_full_logged_total 5328
telemt_desync_suppressed_total 10704
telemt_desync_frames_bucket_total{bucket="1_2"} 3336
telemt_desync_frames_bucket_total{bucket="3_10"} 5773
telemt_desync_frames_bucket_total{bucket="gt_10"} 6923
telemt_pool_swap_total 75
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 9485
telemt_me_writer_restored_same_endpoint_total 9324
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 3351084
telemt_user_connections_current{user="hello"} 6439
telemt_user_octets_from_client{user="hello"} 71785124732 (66.86 GB)
telemt_user_octets_to_client{user="hello"} 1692408748440 (1.54 TB)
telemt_user_unique_ips_current{user="hello"} 2031
telemt_user_unique_ips_recent_window{user="hello"} 777
```