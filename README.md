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

# Server Metrics 2026-03-20 08:39:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 55290.5 (15h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1232178
telemt_connections_bad_total 67245
telemt_connections_current 1769
telemt_connections_me_current 1769
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32303
telemt_upstream_connect_attempt_total 10675
telemt_upstream_connect_success_total 10561
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 10675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 6746
telemt_me_reconnect_success_total 6694
telemt_me_reader_eof_total 7084
telemt_me_idle_close_by_peer_total 7082
telemt_me_route_drop_no_conn_total 361416
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1015814
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5148
telemt_desync_full_logged_total 1855
telemt_desync_suppressed_total 3293
telemt_desync_frames_bucket_total{bucket="1_2"} 1065
telemt_desync_frames_bucket_total{bucket="3_10"} 2003
telemt_desync_frames_bucket_total{bucket="gt_10"} 2080
telemt_pool_swap_total 58
telemt_me_writer_close_signal_drop_total 100
telemt_me_writer_removed_unexpected_total 6765
telemt_me_writer_restored_same_endpoint_total 6681
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1015340
telemt_user_connections_current{user="hello"} 1769
telemt_user_octets_from_client{user="hello"} 38565036792 (35.92 GB)
telemt_user_octets_to_client{user="hello"} 346364187593 (322.58 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 71746.1 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5329349
telemt_connections_bad_total 470286
telemt_connections_current 3994
telemt_connections_me_current 3994
telemt_handshake_timeouts_total 111973
telemt_upstream_connect_attempt_total 13235
telemt_upstream_connect_success_total 12955
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 13235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12452
telemt_me_reconnect_success_total 8172
telemt_me_reader_eof_total 8739
telemt_me_idle_close_by_peer_total 8738
telemt_me_route_drop_no_conn_total 3202132
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4395457
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16339
telemt_desync_full_logged_total 5424
telemt_desync_suppressed_total 10915
telemt_desync_frames_bucket_total{bucket="1_2"} 3263
telemt_desync_frames_bucket_total{bucket="3_10"} 6368
telemt_desync_frames_bucket_total{bucket="gt_10"} 6708
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 114
telemt_me_writer_removed_unexpected_total 8422
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8117
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 4397618
telemt_user_connections_current{user="hello"} 3994
telemt_user_octets_from_client{user="hello"} 59492916910 (55.41 GB)
telemt_user_octets_to_client{user="hello"} 1470553228790 (1.34 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1399
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 5088.3 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282958
telemt_connections_bad_total 23906
telemt_connections_current 2635
telemt_connections_me_current 2635
telemt_handshake_timeouts_total 2985
telemt_upstream_connect_attempt_total 974
telemt_upstream_connect_success_total 974
telemt_upstream_connect_attempts_per_request{bucket="1"} 974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 642
telemt_me_reconnect_success_total 632
telemt_me_reader_eof_total 613
telemt_me_idle_close_by_peer_total 613
telemt_me_route_drop_no_conn_total 95036
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230015
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1098
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 735
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 501
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 617
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 230265
telemt_user_connections_current{user="hello"} 2635
telemt_user_octets_from_client{user="hello"} 3650471732 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 92275879555 (85.94 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1020
telemt_user_unique_ips_recent_window{user="hello"} 404
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 71712.0 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6327584
telemt_connections_bad_total 315338
telemt_connections_current 5233
telemt_connections_me_current 5233
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 85776
telemt_upstream_connect_attempt_total 82872
telemt_upstream_connect_success_total 71119
telemt_upstream_connect_fail_total 11753
telemt_upstream_connect_attempts_per_request{bucket="1"} 82872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11753
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11327
telemt_me_reconnect_success_total 8192
telemt_me_reader_eof_total 8534
telemt_me_idle_close_by_peer_total 8532
telemt_me_route_drop_no_conn_total 8929335
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5425624
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
telemt_desync_total 14501
telemt_desync_full_logged_total 4177
telemt_desync_suppressed_total 10324
telemt_desync_frames_bucket_total{bucket="1_2"} 3246
telemt_desync_frames_bucket_total{bucket="3_10"} 5793
telemt_desync_frames_bucket_total{bucket="gt_10"} 5462
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 833
telemt_me_writer_removed_unexpected_total 9032
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8188
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 840
telemt_user_connections_total{user="hello"} 5484920
telemt_user_connections_current{user="hello"} 5233
telemt_user_octets_from_client{user="hello"} 51431156755 (47.90 GB)
telemt_user_octets_to_client{user="hello"} 907320304225 (845.01 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1566
telemt_user_unique_ips_recent_window{user="hello"} 920
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 9295.1 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2051379
telemt_connections_bad_total 142097
telemt_connections_current 5863
telemt_connections_me_current 5863
telemt_handshake_timeouts_total 24532
telemt_upstream_connect_attempt_total 1613
telemt_upstream_connect_success_total 1602
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 1090
telemt_me_reconnect_success_total 1087
telemt_me_reader_eof_total 1104
telemt_me_idle_close_by_peer_total 1103
telemt_me_route_drop_no_conn_total 3289441
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1755845
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3626
telemt_desync_full_logged_total 1051
telemt_desync_suppressed_total 2575
telemt_desync_frames_bucket_total{bucket="1_2"} 689
telemt_desync_frames_bucket_total{bucket="3_10"} 1476
telemt_desync_frames_bucket_total{bucket="gt_10"} 1461
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 1092
telemt_me_writer_restored_same_endpoint_total 1057
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1750658
telemt_user_connections_current{user="hello"} 5863
telemt_user_octets_from_client{user="hello"} 15347512348 (14.29 GB)
telemt_user_octets_to_client{user="hello"} 220268641436 (205.14 GB)
telemt_user_unique_ips_current{user="hello"} 1875
telemt_user_unique_ips_recent_window{user="hello"} 830
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 9231.5 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145261
telemt_connections_bad_total 18355
telemt_connections_current 733
telemt_connections_me_current 733
telemt_handshake_timeouts_total 1694
telemt_upstream_connect_attempt_total 1680
telemt_upstream_connect_success_total 1666
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1161
telemt_me_reconnect_success_total 1151
telemt_me_reader_eof_total 1195
telemt_me_idle_close_by_peer_total 1195
telemt_me_route_drop_no_conn_total 76853
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136691
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 442
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 1165
telemt_me_writer_restored_same_endpoint_total 1143
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 117878
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 1704718448 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 46168958824 (43.00 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 71676.6 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3500233
telemt_connections_bad_total 225834
telemt_connections_current 5534
telemt_connections_me_current 5534
telemt_handshake_timeouts_total 70160
telemt_upstream_connect_attempt_total 12514
telemt_upstream_connect_success_total 12435
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 12514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 8938
telemt_me_reconnect_success_total 8878
telemt_me_reader_eof_total 9391
telemt_me_idle_close_by_peer_total 9391
telemt_me_route_drop_no_conn_total 1202006
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2944249
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14361
telemt_desync_full_logged_total 4783
telemt_desync_suppressed_total 9578
telemt_desync_frames_bucket_total{bucket="1_2"} 2841
telemt_desync_frames_bucket_total{bucket="3_10"} 5183
telemt_desync_frames_bucket_total{bucket="gt_10"} 6337
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 9008
telemt_me_writer_restored_same_endpoint_total 8861
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 2942215
telemt_user_connections_current{user="hello"} 5534
telemt_user_octets_from_client{user="hello"} 62270008372 (57.99 GB)
telemt_user_octets_to_client{user="hello"} 1527719829624 (1.39 TB)
telemt_user_unique_ips_current{user="hello"} 1793
telemt_user_unique_ips_recent_window{user="hello"} 724
```