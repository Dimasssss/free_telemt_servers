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

# Server Metrics 2026-03-20 08:44:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 55596.2 (15h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1244846
telemt_connections_bad_total 67910
telemt_connections_current 1753
telemt_connections_me_current 1753
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32712
telemt_upstream_connect_attempt_total 10698
telemt_upstream_connect_success_total 10584
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 10698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 6769
telemt_me_reconnect_success_total 6717
telemt_me_reader_eof_total 7107
telemt_me_idle_close_by_peer_total 7105
telemt_me_route_drop_no_conn_total 365416
telemt_me_route_drop_channel_closed_total 192
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1025893
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5195
telemt_desync_full_logged_total 1875
telemt_desync_suppressed_total 3320
telemt_desync_frames_bucket_total{bucket="1_2"} 1078
telemt_desync_frames_bucket_total{bucket="3_10"} 2020
telemt_desync_frames_bucket_total{bucket="gt_10"} 2097
telemt_pool_swap_total 58
telemt_me_writer_close_signal_drop_total 100
telemt_me_writer_removed_unexpected_total 6788
telemt_me_writer_restored_same_endpoint_total 6704
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1025431
telemt_user_connections_current{user="hello"} 1753
telemt_user_octets_from_client{user="hello"} 38820850748 (36.15 GB)
telemt_user_octets_to_client{user="hello"} 349415552897 (325.42 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 632
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 72051.6 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5354093
telemt_connections_bad_total 471222
telemt_connections_current 4100
telemt_connections_me_current 4100
telemt_handshake_timeouts_total 112355
telemt_upstream_connect_attempt_total 13283
telemt_upstream_connect_success_total 13003
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 13283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12491
telemt_me_reconnect_success_total 8211
telemt_me_reader_eof_total 8779
telemt_me_idle_close_by_peer_total 8778
telemt_me_route_drop_no_conn_total 3213350
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4416082
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16426
telemt_desync_full_logged_total 5464
telemt_desync_suppressed_total 10962
telemt_desync_frames_bucket_total{bucket="1_2"} 3276
telemt_desync_frames_bucket_total{bucket="3_10"} 6404
telemt_desync_frames_bucket_total{bucket="gt_10"} 6746
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 116
telemt_me_writer_removed_unexpected_total 8461
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8156
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 4418236
telemt_user_connections_current{user="hello"} 4100
telemt_user_octets_from_client{user="hello"} 59850017106 (55.74 GB)
telemt_user_octets_to_client{user="hello"} 1478910938074 (1.35 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1449
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 5393.2 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303261
telemt_connections_bad_total 25149
telemt_connections_current 2752
telemt_connections_me_current 2752
telemt_handshake_timeouts_total 3209
telemt_upstream_connect_attempt_total 1015
telemt_upstream_connect_success_total 1015
telemt_upstream_connect_attempts_per_request{bucket="1"} 1015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 683
telemt_me_reconnect_success_total 673
telemt_me_reader_eof_total 654
telemt_me_idle_close_by_peer_total 654
telemt_me_route_drop_no_conn_total 102028
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247909
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1170
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 782
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 536
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 658
telemt_me_writer_restored_same_endpoint_total 673
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 248149
telemt_user_connections_current{user="hello"} 2752
telemt_user_octets_from_client{user="hello"} 3917965384 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 99606918559 (92.77 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1056
telemt_user_unique_ips_recent_window{user="hello"} 414
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 72029.6 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4823406
telemt_connections_bad_total 586096
telemt_connections_current 5132
telemt_connections_me_current 5132
telemt_handshake_timeouts_total 71001
telemt_upstream_connect_attempt_total 12955
telemt_upstream_connect_success_total 12846
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 12955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 8784
telemt_me_reconnect_success_total 7815
telemt_me_reader_eof_total 8189
telemt_me_idle_close_by_peer_total 8184
telemt_me_route_drop_no_conn_total 2988044
telemt_me_route_drop_channel_closed_total 302
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3481382
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12135
telemt_desync_full_logged_total 3861
telemt_desync_suppressed_total 8274
telemt_desync_frames_bucket_total{bucket="1_2"} 2851
telemt_desync_frames_bucket_total{bucket="3_10"} 4578
telemt_desync_frames_bucket_total{bucket="gt_10"} 4706
telemt_pool_swap_total 71
telemt_me_writer_close_signal_drop_total 357
telemt_me_writer_removed_unexpected_total 7922
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7814
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 3487743
telemt_user_connections_current{user="hello"} 5132
telemt_user_octets_from_client{user="hello"} 52114340306 (48.54 GB)
telemt_user_octets_to_client{user="hello"} 1304945915616 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1642
telemt_user_unique_ips_recent_window{user="hello"} 759
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 72032.6 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6424325
telemt_connections_bad_total 317190
telemt_connections_current 5054
telemt_connections_me_current 5054
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 86904
telemt_upstream_connect_attempt_total 82905
telemt_upstream_connect_success_total 71150
telemt_upstream_connect_fail_total 11755
telemt_upstream_connect_attempts_per_request{bucket="1"} 82905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11755
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11354
telemt_me_reconnect_success_total 8217
telemt_me_reader_eof_total 8562
telemt_me_idle_close_by_peer_total 8560
telemt_me_route_drop_no_conn_total 9138617
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5514274
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
telemt_desync_total 14598
telemt_desync_full_logged_total 4209
telemt_desync_suppressed_total 10389
telemt_desync_frames_bucket_total{bucket="1_2"} 3261
telemt_desync_frames_bucket_total{bucket="3_10"} 5829
telemt_desync_frames_bucket_total{bucket="gt_10"} 5508
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 834
telemt_me_writer_removed_unexpected_total 9060
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8213
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 843
telemt_user_connections_total{user="hello"} 5573602
telemt_user_connections_current{user="hello"} 5054
telemt_user_octets_from_client{user="hello"} 51790868591 (48.23 GB)
telemt_user_octets_to_client{user="hello"} 911335765577 (848.75 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1545
telemt_user_unique_ips_recent_window{user="hello"} 793
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 9600.5 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2123696
telemt_connections_bad_total 150945
telemt_connections_current 5554
telemt_connections_me_current 5554
telemt_handshake_timeouts_total 25256
telemt_upstream_connect_attempt_total 1652
telemt_upstream_connect_success_total 1641
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 1129
telemt_me_reconnect_success_total 1125
telemt_me_reader_eof_total 1143
telemt_me_idle_close_by_peer_total 1142
telemt_me_route_drop_no_conn_total 3371672
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1812445
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3750
telemt_desync_full_logged_total 1088
telemt_desync_suppressed_total 2662
telemt_desync_frames_bucket_total{bucket="1_2"} 720
telemt_desync_frames_bucket_total{bucket="3_10"} 1520
telemt_desync_frames_bucket_total{bucket="gt_10"} 1510
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 1131
telemt_me_writer_restored_same_endpoint_total 1095
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1807261
telemt_user_connections_current{user="hello"} 5554
telemt_user_octets_from_client{user="hello"} 15769083028 (14.69 GB)
telemt_user_octets_to_client{user="hello"} 227618188140 (211.99 GB)
telemt_user_unique_ips_current{user="hello"} 1815
telemt_user_unique_ips_recent_window{user="hello"} 799
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 9535.7 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150068
telemt_connections_bad_total 18491
telemt_connections_current 709
telemt_connections_me_current 709
telemt_handshake_timeouts_total 1715
telemt_upstream_connect_attempt_total 1749
telemt_upstream_connect_success_total 1735
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 857
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1230
telemt_me_reconnect_success_total 1220
telemt_me_reader_eof_total 1265
telemt_me_idle_close_by_peer_total 1265
telemt_me_route_drop_no_conn_total 79626
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141750
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 450
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 1235
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 122339
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 1759557600 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 47847011836 (44.56 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 71981.9 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3553423
telemt_connections_bad_total 227886
telemt_connections_current 5540
telemt_connections_me_current 5540
telemt_handshake_timeouts_total 72010
telemt_upstream_connect_attempt_total 12530
telemt_upstream_connect_success_total 12451
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 12530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 8954
telemt_me_reconnect_success_total 8893
telemt_me_reader_eof_total 9408
telemt_me_idle_close_by_peer_total 9408
telemt_me_route_drop_no_conn_total 1277858
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2991990
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14502
telemt_desync_full_logged_total 4836
telemt_desync_suppressed_total 9666
telemt_desync_frames_bucket_total{bucket="1_2"} 2872
telemt_desync_frames_bucket_total{bucket="3_10"} 5243
telemt_desync_frames_bucket_total{bucket="gt_10"} 6387
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 9025
telemt_me_writer_restored_same_endpoint_total 8876
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 2989972
telemt_user_connections_current{user="hello"} 5540
telemt_user_octets_from_client{user="hello"} 62653239624 (58.35 GB)
telemt_user_octets_to_client{user="hello"} 1538356331604 (1.40 TB)
telemt_user_unique_ips_current{user="hello"} 1760
telemt_user_unique_ips_recent_window{user="hello"} 687
```