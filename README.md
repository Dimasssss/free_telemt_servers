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

# Server Metrics 2026-03-20 09:45:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 59270.8 (16h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1405254
telemt_connections_bad_total 73696
telemt_connections_current 2107
telemt_connections_me_current 2107
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 36433
telemt_upstream_connect_attempt_total 11293
telemt_upstream_connect_success_total 11174
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 11293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 7185
telemt_me_reconnect_success_total 7130
telemt_me_reader_eof_total 7543
telemt_me_idle_close_by_peer_total 7541
telemt_me_route_drop_no_conn_total 421383
telemt_me_route_drop_channel_closed_total 260
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1152857
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6170
telemt_desync_full_logged_total 2167
telemt_desync_suppressed_total 4003
telemt_desync_frames_bucket_total{bucket="1_2"} 1335
telemt_desync_frames_bucket_total{bucket="3_10"} 2377
telemt_desync_frames_bucket_total{bucket="gt_10"} 2458
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 142
telemt_me_writer_removed_unexpected_total 7208
telemt_me_writer_restored_same_endpoint_total 7117
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1152532
telemt_user_connections_current{user="hello"} 2106
telemt_user_octets_from_client{user="hello"} 41107859828 (38.28 GB)
telemt_user_octets_to_client{user="hello"} 389940219229 (363.16 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 706
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 75726.3 (21h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5768471
telemt_connections_bad_total 510974
telemt_connections_current 4026
telemt_connections_me_current 4026
telemt_handshake_timeouts_total 118620
telemt_upstream_connect_attempt_total 13994
telemt_upstream_connect_success_total 13695
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 13993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 13074
telemt_me_reconnect_success_total 8692
telemt_me_reader_eof_total 9284
telemt_me_idle_close_by_peer_total 9283
telemt_me_route_drop_no_conn_total 3583333
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4745778
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17442
telemt_desync_full_logged_total 5862
telemt_desync_suppressed_total 11580
telemt_desync_frames_bucket_total{bucket="1_2"} 3492
telemt_desync_frames_bucket_total{bucket="3_10"} 6839
telemt_desync_frames_bucket_total{bucket="gt_10"} 7111
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3394
telemt_me_writer_close_signal_drop_total 128
telemt_me_writer_removed_unexpected_total 8953
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 8637
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 4747280
telemt_user_connections_current{user="hello"} 4026
telemt_user_octets_from_client{user="hello"} 64114536466 (59.71 GB)
telemt_user_octets_to_client{user="hello"} 1567523543014 (1.43 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1460
telemt_user_unique_ips_recent_window{user="hello"} 567
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 9068.5 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592065
telemt_connections_bad_total 55231
telemt_connections_current 3432
telemt_connections_me_current 3432
telemt_handshake_timeouts_total 6537
telemt_upstream_connect_attempt_total 1687
telemt_upstream_connect_success_total 1687
telemt_upstream_connect_attempts_per_request{bucket="1"} 1687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1152
telemt_me_reconnect_success_total 1139
telemt_me_reader_eof_total 1151
telemt_me_idle_close_by_peer_total 1151
telemt_me_route_drop_no_conn_total 213726
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479066
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1996
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1344
telemt_desync_frames_bucket_total{bucket="1_2"} 392
telemt_desync_frames_bucket_total{bucket="3_10"} 698
telemt_desync_frames_bucket_total{bucket="gt_10"} 906
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 1133
telemt_me_writer_restored_same_endpoint_total 1139
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 479319
telemt_user_connections_current{user="hello"} 3432
telemt_user_octets_from_client{user="hello"} 7683343504 (7.16 GB)
telemt_user_octets_to_client{user="hello"} 184736762411 (172.05 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1306
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 75692.2 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7758632
telemt_connections_bad_total 341771
telemt_connections_current 6962
telemt_connections_me_current 6962
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 100867
telemt_upstream_connect_attempt_total 83468
telemt_upstream_connect_success_total 71681
telemt_upstream_connect_fail_total 11787
telemt_upstream_connect_attempts_per_request{bucket="1"} 83468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11787
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 11711
telemt_me_reconnect_success_total 8553
telemt_me_reader_eof_total 8926
telemt_me_idle_close_by_peer_total 8924
telemt_me_route_drop_no_conn_total 12288044
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6730416
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
telemt_desync_total 15848
telemt_desync_full_logged_total 4617
telemt_desync_suppressed_total 11231
telemt_desync_frames_bucket_total{bucket="1_2"} 3511
telemt_desync_frames_bucket_total{bucket="3_10"} 6358
telemt_desync_frames_bucket_total{bucket="gt_10"} 5979
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 850
telemt_me_writer_removed_unexpected_total 9412
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8549
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 859
telemt_user_connections_total{user="hello"} 6789814
telemt_user_connections_current{user="hello"} 6962
telemt_user_octets_from_client{user="hello"} 56888945467 (52.98 GB)
telemt_user_octets_to_client{user="hello"} 952576808969 (887.16 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1736
telemt_user_unique_ips_recent_window{user="hello"} 1123
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 13275.4 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2973471
telemt_connections_bad_total 242699
telemt_connections_current 6416
telemt_connections_me_current 6416
telemt_handshake_timeouts_total 34039
telemt_upstream_connect_attempt_total 2199
telemt_upstream_connect_success_total 2186
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 1497
telemt_me_reconnect_success_total 1488
telemt_me_reader_eof_total 1536
telemt_me_idle_close_by_peer_total 1535
telemt_me_route_drop_no_conn_total 4575767
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2511024
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5382
telemt_desync_full_logged_total 1551
telemt_desync_suppressed_total 3831
telemt_desync_frames_bucket_total{bucket="1_2"} 983
telemt_desync_frames_bucket_total{bucket="3_10"} 2206
telemt_desync_frames_bucket_total{bucket="gt_10"} 2193
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 46
telemt_me_writer_removed_unexpected_total 1504
telemt_me_writer_restored_same_endpoint_total 1458
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 2505797
telemt_user_connections_current{user="hello"} 6416
telemt_user_octets_from_client{user="hello"} 21568840680 (20.09 GB)
telemt_user_octets_to_client{user="hello"} 315419862816 (293.76 GB)
telemt_user_unique_ips_current{user="hello"} 2015
telemt_user_unique_ips_recent_window{user="hello"} 894
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 2852.7 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64917
telemt_connections_bad_total 14182
telemt_connections_current 864
telemt_connections_me_current 864
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 1343
telemt_upstream_connect_attempt_total 2043
telemt_upstream_connect_success_total 2025
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 458
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 413
telemt_me_idle_close_by_peer_total 413
telemt_me_route_drop_no_conn_total 19831
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45668
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 21
telemt_me_writer_removed_unexpected_total 419
telemt_me_writer_restored_same_endpoint_total 452
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 47188
telemt_user_connections_current{user="hello"} 864
telemt_user_octets_from_client{user="hello"} 791188991 (754.54 MB)
telemt_user_octets_to_client{user="hello"} 8029453704 (7.48 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 75657.4 (21h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4013436
telemt_connections_bad_total 252436
telemt_connections_current 6485
telemt_connections_me_current 6485
telemt_handshake_timeouts_total 88203
telemt_upstream_connect_attempt_total 13202
telemt_upstream_connect_success_total 13118
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 13202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9425
telemt_me_reconnect_success_total 9357
telemt_me_reader_eof_total 9901
telemt_me_idle_close_by_peer_total 9900
telemt_me_route_drop_no_conn_total 1440477
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3387776
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16175
telemt_desync_full_logged_total 5375
telemt_desync_suppressed_total 10800
telemt_desync_frames_bucket_total{bucket="1_2"} 3373
telemt_desync_frames_bucket_total{bucket="3_10"} 5820
telemt_desync_frames_bucket_total{bucket="gt_10"} 6982
telemt_pool_swap_total 75
telemt_me_writer_close_signal_drop_total 57
telemt_me_writer_removed_unexpected_total 9501
telemt_me_writer_restored_same_endpoint_total 9340
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 3385679
telemt_user_connections_current{user="hello"} 6485
telemt_user_octets_from_client{user="hello"} 72694300288 (67.70 GB)
telemt_user_octets_to_client{user="hello"} 1706309115892 (1.55 TB)
telemt_user_unique_ips_current{user="hello"} 2015
telemt_user_unique_ips_recent_window{user="hello"} 805
```