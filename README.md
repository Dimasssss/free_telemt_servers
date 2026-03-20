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

# Server Metrics 2026-03-20 07:37:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 51617.4 (14h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1093380
telemt_connections_bad_total 64278
telemt_connections_current 1714
telemt_connections_me_current 1714
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 28076
telemt_upstream_connect_attempt_total 9987
telemt_upstream_connect_success_total 9878
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 9987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6239
telemt_me_reconnect_success_total 6192
telemt_me_reader_eof_total 6557
telemt_me_idle_close_by_peer_total 6556
telemt_me_route_drop_no_conn_total 316560
telemt_me_route_drop_channel_closed_total 147
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 898458
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4568
telemt_desync_full_logged_total 1644
telemt_desync_suppressed_total 2924
telemt_desync_frames_bucket_total{bucket="1_2"} 923
telemt_desync_frames_bucket_total{bucket="3_10"} 1764
telemt_desync_frames_bucket_total{bucket="gt_10"} 1881
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 75
telemt_me_writer_removed_unexpected_total 6260
telemt_me_writer_restored_same_endpoint_total 6179
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 897882
telemt_user_connections_current{user="hello"} 1714
telemt_user_octets_from_client{user="hello"} 35810469140 (33.35 GB)
telemt_user_octets_to_client{user="hello"} 308734975397 (287.53 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 599
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 68072.8 (18h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5015020
telemt_connections_bad_total 445327
telemt_connections_current 3651
telemt_connections_me_current 3651
telemt_handshake_timeouts_total 106319
telemt_upstream_connect_attempt_total 12651
telemt_upstream_connect_success_total 12390
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 12651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12059
telemt_me_reconnect_success_total 7786
telemt_me_reader_eof_total 8333
telemt_me_idle_close_by_peer_total 8332
telemt_me_route_drop_no_conn_total 3086765
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4141082
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15334
telemt_desync_full_logged_total 5053
telemt_desync_suppressed_total 10281
telemt_desync_frames_bucket_total{bucket="1_2"} 3019
telemt_desync_frames_bucket_total{bucket="3_10"} 5986
telemt_desync_frames_bucket_total{bucket="gt_10"} 6329
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 109
telemt_me_writer_removed_unexpected_total 8029
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7731
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 4142954
telemt_user_connections_current{user="hello"} 3651
telemt_user_octets_from_client{user="hello"} 55199772038 (51.41 GB)
telemt_user_octets_to_client{user="hello"} 1375570077706 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1300
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 1414.9 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45812
telemt_connections_bad_total 4189
telemt_connections_current 2191
telemt_connections_me_current 2191
telemt_handshake_timeouts_total 428
telemt_upstream_connect_attempt_total 370
telemt_upstream_connect_success_total 370
telemt_upstream_connect_attempts_per_request{bucket="1"} 370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 212
telemt_me_reconnect_success_total 209
telemt_me_reader_eof_total 174
telemt_me_idle_close_by_peer_total 174
telemt_me_route_drop_no_conn_total 15645
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39007
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 263
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 192
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 189
telemt_me_writer_restored_same_endpoint_total 209
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 39078
telemt_user_connections_current{user="hello"} 2191
telemt_user_octets_from_client{user="hello"} 721410500 (687.99 MB)
telemt_user_octets_to_client{user="hello"} 13205415351 (12.30 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 328
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 68038.6 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4993274
telemt_connections_bad_total 295328
telemt_connections_current 5099
telemt_connections_me_current 5099
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 69320
telemt_upstream_connect_attempt_total 68359
telemt_upstream_connect_success_total 63612
telemt_upstream_connect_fail_total 4747
telemt_upstream_connect_attempts_per_request{bucket="1"} 68359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 713
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4747
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 10823
telemt_me_reconnect_success_total 7831
telemt_me_reader_eof_total 8180
telemt_me_idle_close_by_peer_total 8179
telemt_me_route_drop_no_conn_total 6260504
telemt_me_route_drop_channel_closed_total 79
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4219703
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13380
telemt_desync_full_logged_total 3859
telemt_desync_suppressed_total 9521
telemt_desync_frames_bucket_total{bucket="1_2"} 2981
telemt_desync_frames_bucket_total{bucket="3_10"} 5299
telemt_desync_frames_bucket_total{bucket="gt_10"} 5100
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 681
telemt_me_writer_removed_unexpected_total 8568
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7827
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 4271136
telemt_user_connections_current{user="hello"} 5099
telemt_user_octets_from_client{user="hello"} 47769916672 (44.49 GB)
telemt_user_octets_to_client{user="hello"} 865979608767 (806.51 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1515
telemt_user_unique_ips_recent_window{user="hello"} 897
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 5621.7 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 950355
telemt_connections_bad_total 90968
telemt_connections_current 5381
telemt_connections_me_current 5381
telemt_handshake_timeouts_total 16438
telemt_upstream_connect_attempt_total 932
telemt_upstream_connect_success_total 928
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 596
telemt_me_reconnect_success_total 594
telemt_me_reader_eof_total 588
telemt_me_idle_close_by_peer_total 588
telemt_me_route_drop_no_conn_total 1186171
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 786749
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 647
telemt_desync_suppressed_total 1459
telemt_desync_frames_bucket_total{bucket="1_2"} 417
telemt_desync_frames_bucket_total{bucket="3_10"} 847
telemt_desync_frames_bucket_total{bucket="gt_10"} 842
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 589
telemt_me_writer_restored_same_endpoint_total 564
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 786717
telemt_user_connections_current{user="hello"} 5381
telemt_user_octets_from_client{user="hello"} 9777589944 (9.11 GB)
telemt_user_octets_to_client{user="hello"} 141415889052 (131.70 GB)
telemt_user_unique_ips_current{user="hello"} 1689
telemt_user_unique_ips_recent_window{user="hello"} 891
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 5557.0 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88137
telemt_connections_bad_total 13690
telemt_connections_current 671
telemt_connections_me_current 671
telemt_handshake_timeouts_total 934
telemt_upstream_connect_attempt_total 1024
telemt_upstream_connect_success_total 1015
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 685
telemt_me_reconnect_success_total 680
telemt_me_reader_eof_total 695
telemt_me_idle_close_by_peer_total 695
telemt_me_route_drop_no_conn_total 45941
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84866
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 269
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_restored_same_endpoint_total 672
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 69674
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 1043045712 (994.73 MB)
telemt_user_octets_to_client{user="hello"} 27715365796 (25.81 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 68003.5 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3096990
telemt_connections_bad_total 206616
telemt_connections_current 4930
telemt_connections_me_current 4930
telemt_handshake_timeouts_total 55975
telemt_upstream_connect_attempt_total 11938
telemt_upstream_connect_success_total 11863
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 11938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8541
telemt_me_reconnect_success_total 8485
telemt_me_reader_eof_total 8971
telemt_me_idle_close_by_peer_total 8971
telemt_me_route_drop_no_conn_total 1049689
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2596822
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12815
telemt_desync_full_logged_total 4164
telemt_desync_suppressed_total 8651
telemt_desync_frames_bucket_total{bucket="1_2"} 2547
telemt_desync_frames_bucket_total{bucket="3_10"} 4555
telemt_desync_frames_bucket_total{bucket="gt_10"} 5713
telemt_pool_swap_total 70
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8605
telemt_me_writer_restored_same_endpoint_total 8468
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 2594938
telemt_user_connections_current{user="hello"} 4930
telemt_user_octets_from_client{user="hello"} 55329948376 (51.53 GB)
telemt_user_octets_to_client{user="hello"} 1357437353540 (1.23 TB)
telemt_user_unique_ips_current{user="hello"} 1545
telemt_user_unique_ips_recent_window{user="hello"} 595
```