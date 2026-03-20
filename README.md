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

# Server Metrics 2026-03-20 07:58:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 52838.1 (14h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1133449
telemt_connections_bad_total 64692
telemt_connections_current 1805
telemt_connections_me_current 1805
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29594
telemt_upstream_connect_attempt_total 10150
telemt_upstream_connect_success_total 10039
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 10150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6357
telemt_me_reconnect_success_total 6309
telemt_me_reader_eof_total 6680
telemt_me_idle_close_by_peer_total 6679
telemt_me_route_drop_no_conn_total 328378
telemt_me_route_drop_channel_closed_total 155
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 933866
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4724
telemt_desync_full_logged_total 1700
telemt_desync_suppressed_total 3024
telemt_desync_frames_bucket_total{bucket="1_2"} 956
telemt_desync_frames_bucket_total{bucket="3_10"} 1825
telemt_desync_frames_bucket_total{bucket="gt_10"} 1943
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 78
telemt_me_writer_removed_unexpected_total 6379
telemt_me_writer_restored_same_endpoint_total 6296
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 933341
telemt_user_connections_current{user="hello"} 1805
telemt_user_octets_from_client{user="hello"} 37308769812 (34.75 GB)
telemt_user_octets_to_client{user="hello"} 320090284865 (298.11 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 69293.6 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5107061
telemt_connections_bad_total 450760
telemt_connections_current 3650
telemt_connections_me_current 3650
telemt_handshake_timeouts_total 108475
telemt_upstream_connect_attempt_total 12822
telemt_upstream_connect_success_total 12557
telemt_upstream_connect_fail_total 265
telemt_upstream_connect_attempts_per_request{bucket="1"} 12822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 265
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12183
telemt_me_reconnect_success_total 7906
telemt_me_reader_eof_total 8457
telemt_me_idle_close_by_peer_total 8456
telemt_me_route_drop_no_conn_total 3114665
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4218591
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15603
telemt_desync_full_logged_total 5153
telemt_desync_suppressed_total 10450
telemt_desync_frames_bucket_total{bucket="1_2"} 3066
telemt_desync_frames_bucket_total{bucket="3_10"} 6086
telemt_desync_frames_bucket_total{bucket="gt_10"} 6451
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 110
telemt_me_writer_removed_unexpected_total 8151
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7851
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 4220713
telemt_user_connections_current{user="hello"} 3650
telemt_user_octets_from_client{user="hello"} 56337199122 (52.47 GB)
telemt_user_octets_to_client{user="hello"} 1404541924106 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1302
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 2635.7 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114825
telemt_connections_bad_total 12259
telemt_connections_current 2455
telemt_connections_me_current 2455
telemt_handshake_timeouts_total 1085
telemt_upstream_connect_attempt_total 537
telemt_upstream_connect_success_total 537
telemt_upstream_connect_attempts_per_request{bucket="1"} 537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 336
telemt_me_reconnect_success_total 331
telemt_me_reader_eof_total 301
telemt_me_idle_close_by_peer_total 301
telemt_me_route_drop_no_conn_total 37789
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96090
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 443
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 311
telemt_me_writer_restored_same_endpoint_total 331
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 96193
telemt_user_connections_current{user="hello"} 2455
telemt_user_octets_from_client{user="hello"} 2047604204 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 36796152019 (34.27 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 890
telemt_user_unique_ips_recent_window{user="hello"} 364
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 69271.7 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4458679
telemt_connections_bad_total 554665
telemt_connections_current 4678
telemt_connections_me_current 4678
telemt_handshake_timeouts_total 67446
telemt_upstream_connect_attempt_total 12598
telemt_upstream_connect_success_total 12492
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3086
telemt_me_reconnect_attempts_total 8564
telemt_me_reconnect_success_total 7600
telemt_me_reader_eof_total 7955
telemt_me_idle_close_by_peer_total 7950
telemt_me_route_drop_no_conn_total 2846948
telemt_me_route_drop_channel_closed_total 278
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3214617
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11365
telemt_desync_full_logged_total 3580
telemt_desync_suppressed_total 7785
telemt_desync_frames_bucket_total{bucket="1_2"} 2698
telemt_desync_frames_bucket_total{bucket="3_10"} 4332
telemt_desync_frames_bucket_total{bucket="gt_10"} 4335
telemt_pool_swap_total 68
telemt_me_writer_close_signal_drop_total 327
telemt_me_writer_removed_unexpected_total 7700
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7599
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 3220999
telemt_user_connections_current{user="hello"} 4678
telemt_user_octets_from_client{user="hello"} 45786508630 (42.64 GB)
telemt_user_octets_to_client{user="hello"} 1203452363624 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1502
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 69259.4 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5452428
telemt_connections_bad_total 300589
telemt_connections_current 5196
telemt_connections_me_current 5196
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 75121
telemt_upstream_connect_attempt_total 82465
telemt_upstream_connect_success_total 70737
telemt_upstream_connect_fail_total 11728
telemt_upstream_connect_attempts_per_request{bucket="1"} 82465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11728
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 11058
telemt_me_reconnect_success_total 7941
telemt_me_reader_eof_total 8270
telemt_me_idle_close_by_peer_total 8268
telemt_me_route_drop_no_conn_total 7122573
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4624060
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
telemt_desync_total 13605
telemt_desync_full_logged_total 3932
telemt_desync_suppressed_total 9673
telemt_desync_frames_bucket_total{bucket="1_2"} 3038
telemt_desync_frames_bucket_total{bucket="3_10"} 5418
telemt_desync_frames_bucket_total{bucket="gt_10"} 5149
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 825
telemt_me_writer_removed_unexpected_total 8768
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7937
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 827
telemt_user_connections_total{user="hello"} 4683322
telemt_user_connections_current{user="hello"} 5196
telemt_user_octets_from_client{user="hello"} 48979005183 (45.62 GB)
telemt_user_octets_to_client{user="hello"} 877944304501 (817.65 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1455
telemt_user_unique_ips_recent_window{user="hello"} 850
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 6842.6 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1328230
telemt_connections_bad_total 100310
telemt_connections_current 5940
telemt_connections_me_current 5940
telemt_handshake_timeouts_total 18684
telemt_upstream_connect_attempt_total 1125
telemt_upstream_connect_success_total 1119
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 742
telemt_me_reconnect_success_total 739
telemt_me_reader_eof_total 736
telemt_me_idle_close_by_peer_total 736
telemt_me_route_drop_no_conn_total 1961863
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1130619
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2505
telemt_desync_full_logged_total 746
telemt_desync_suppressed_total 1759
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 1014
telemt_desync_frames_bucket_total{bucket="gt_10"} 1006
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 737
telemt_me_writer_restored_same_endpoint_total 709
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 1130558
telemt_user_connections_current{user="hello"} 5940
telemt_user_octets_from_client{user="hello"} 11657452524 (10.86 GB)
telemt_user_octets_to_client{user="hello"} 168204326804 (156.65 GB)
telemt_user_unique_ips_current{user="hello"} 1763
telemt_user_unique_ips_recent_window{user="hello"} 917
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 6778.4 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105083
telemt_connections_bad_total 14081
telemt_connections_current 633
telemt_connections_me_current 633
telemt_handshake_timeouts_total 1268
telemt_upstream_connect_attempt_total 1232
telemt_upstream_connect_success_total 1222
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 849
telemt_me_reconnect_success_total 844
telemt_me_reader_eof_total 869
telemt_me_idle_close_by_peer_total 869
telemt_me_route_drop_no_conn_total 54457
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101523
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 210
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 851
telemt_me_writer_restored_same_endpoint_total 836
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 85064
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 1297512180 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 34311625444 (31.96 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 69224.3 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3221133
telemt_connections_bad_total 212929
telemt_connections_current 5463
telemt_connections_me_current 5463
telemt_handshake_timeouts_total 58352
telemt_upstream_connect_attempt_total 12075
telemt_upstream_connect_success_total 12000
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 12075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8635
telemt_me_reconnect_success_total 8578
telemt_me_reader_eof_total 9070
telemt_me_idle_close_by_peer_total 9070
telemt_me_route_drop_no_conn_total 1097959
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2704832
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13249
telemt_desync_full_logged_total 4340
telemt_desync_suppressed_total 8909
telemt_desync_frames_bucket_total{bucket="1_2"} 2634
telemt_desync_frames_bucket_total{bucket="3_10"} 4738
telemt_desync_frames_bucket_total{bucket="gt_10"} 5877
telemt_pool_swap_total 71
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8701
telemt_me_writer_restored_same_endpoint_total 8561
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 2702770
telemt_user_connections_current{user="hello"} 5463
telemt_user_octets_from_client{user="hello"} 57552090432 (53.60 GB)
telemt_user_octets_to_client{user="hello"} 1408329151900 (1.28 TB)
telemt_user_unique_ips_current{user="hello"} 1687
telemt_user_unique_ips_recent_window{user="hello"} 647
```