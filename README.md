# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

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

# Server Metrics 2026-03-20 00:27:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 25813.1 (7h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508221
telemt_connections_bad_total 32852
telemt_connections_current 872
telemt_connections_me_current 872
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7474
telemt_upstream_connect_attempt_total 5583
telemt_upstream_connect_success_total 5508
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 5583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3123
telemt_me_reconnect_success_total 3093
telemt_me_reader_eof_total 3251
telemt_me_idle_close_by_peer_total 3250
telemt_me_route_drop_no_conn_total 149120
telemt_me_route_drop_channel_closed_total 55
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403626
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2013
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1296
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 673
telemt_desync_frames_bucket_total{bucket="gt_10"} 927
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3110
telemt_me_writer_restored_same_endpoint_total 3080
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 405045
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 29238529484 (27.23 GB)
telemt_user_octets_to_client{user="hello"} 146139451861 (136.10 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 42268.6 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2931091
telemt_connections_bad_total 125108
telemt_connections_current 1276
telemt_connections_me_current 1276
telemt_handshake_timeouts_total 63201
telemt_upstream_connect_attempt_total 8472
telemt_upstream_connect_success_total 8333
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 8472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9244
telemt_me_reconnect_success_total 5006
telemt_me_reader_eof_total 5351
telemt_me_idle_close_by_peer_total 5351
telemt_me_route_drop_no_conn_total 1484750
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2507128
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10816
telemt_desync_full_logged_total 3574
telemt_desync_suppressed_total 7242
telemt_desync_frames_bucket_total{bucket="1_2"} 2035
telemt_desync_frames_bucket_total{bucket="3_10"} 4244
telemt_desync_frames_bucket_total{bucket="gt_10"} 4537
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5192
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4951
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 2506945
telemt_user_connections_current{user="hello"} 1276
telemt_user_octets_from_client{user="hello"} 38771002762 (36.11 GB)
telemt_user_octets_to_client{user="hello"} 909233426850 (846.79 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 624
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 42246.7 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2862744
telemt_connections_bad_total 469478
telemt_connections_current 1023
telemt_connections_me_current 1023
telemt_handshake_timeouts_total 40055
telemt_upstream_connect_attempt_total 6691
telemt_upstream_connect_success_total 6642
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 6691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5474
telemt_me_reconnect_success_total 4543
telemt_me_reader_eof_total 4753
telemt_me_idle_close_by_peer_total 4752
telemt_me_route_drop_no_conn_total 1901798
telemt_me_route_drop_channel_closed_total 171
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1985172
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7567
telemt_desync_full_logged_total 2288
telemt_desync_suppressed_total 5279
telemt_desync_frames_bucket_total{bucket="1_2"} 1865
telemt_desync_frames_bucket_total{bucket="3_10"} 2880
telemt_desync_frames_bucket_total{bucket="gt_10"} 2822
telemt_pool_swap_total 40
telemt_me_writer_close_signal_drop_total 67
telemt_me_writer_removed_unexpected_total 4587
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4542
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1980884
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 29519712976 (27.49 GB)
telemt_user_octets_to_client{user="hello"} 754579842132 (702.76 GB)
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 42234.6 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2484851
telemt_connections_bad_total 107282
telemt_connections_current 969
telemt_connections_me_current 969
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30390
telemt_upstream_connect_attempt_total 53678
telemt_upstream_connect_success_total 49501
telemt_upstream_connect_fail_total 4177
telemt_upstream_connect_attempts_per_request{bucket="1"} 53678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 522
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4177
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7857
telemt_me_reconnect_success_total 5081
telemt_me_reader_eof_total 5272
telemt_me_idle_close_by_peer_total 5271
telemt_me_route_drop_no_conn_total 1851204
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2089551
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8221
telemt_desync_full_logged_total 2593
telemt_desync_suppressed_total 5628
telemt_desync_frames_bucket_total{bucket="1_2"} 2013
telemt_desync_frames_bucket_total{bucket="3_10"} 2987
telemt_desync_frames_bucket_total{bucket="gt_10"} 3221
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 404
telemt_me_writer_removed_unexpected_total 5661
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5077
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 2130702
telemt_user_connections_current{user="hello"} 969
telemt_user_octets_from_client{user="hello"} 35035291227 (32.63 GB)
telemt_user_octets_to_client{user="hello"} 593998304823 (553.20 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 95957.9 (26h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6204491
telemt_connections_bad_total 1039186
telemt_connections_current 1217
telemt_connections_me_current 1217
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 111796
telemt_upstream_connect_attempt_total 126670
telemt_upstream_connect_success_total 93387
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 126670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1429
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77949
telemt_me_reconnect_success_total 12282
telemt_me_reader_eof_total 13238
telemt_me_idle_close_by_peer_total 13224
telemt_me_route_drop_no_conn_total 2778970
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4386586
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19300
telemt_desync_full_logged_total 6096
telemt_desync_suppressed_total 13204
telemt_desync_frames_bucket_total{bucket="1_2"} 3368
telemt_desync_frames_bucket_total{bucket="3_10"} 7929
telemt_desync_frames_bucket_total{bucket="gt_10"} 8003
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 12586
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12257
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 4461801
telemt_user_connections_current{user="hello"} 1217
telemt_user_octets_from_client{user="hello"} 69125285500 (64.38 GB)
telemt_user_octets_to_client{user="hello"} 1722258474044 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 42197.7 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688367
telemt_connections_bad_total 70756
telemt_connections_current 299
telemt_connections_me_current 299
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12901
telemt_upstream_connect_attempt_total 12716
telemt_upstream_connect_success_total 12386
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6436
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 660
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5940
telemt_me_reconnect_success_total 5835
telemt_me_reader_eof_total 6100
telemt_me_idle_close_by_peer_total 6097
telemt_me_route_drop_no_conn_total 461853
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 567009
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 36
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5887
telemt_me_writer_restored_same_endpoint_total 5826
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 555153
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 7147660055 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 135586627502 (126.27 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 42199.1 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1974017
telemt_connections_bad_total 117955
telemt_connections_current 1070
telemt_connections_me_current 1070
telemt_handshake_timeouts_total 36593
telemt_upstream_connect_attempt_total 7379
telemt_upstream_connect_success_total 7324
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 7379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5255
telemt_me_reconnect_success_total 5216
telemt_me_reader_eof_total 5504
telemt_me_idle_close_by_peer_total 5504
telemt_me_route_drop_no_conn_total 730569
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1701073
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9026
telemt_desync_full_logged_total 2892
telemt_desync_suppressed_total 6134
telemt_desync_frames_bucket_total{bucket="1_2"} 1669
telemt_desync_frames_bucket_total{bucket="3_10"} 3181
telemt_desync_frames_bucket_total{bucket="gt_10"} 4176
telemt_pool_swap_total 41
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 5299
telemt_me_writer_restored_same_endpoint_total 5199
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 1700190
telemt_user_connections_current{user="hello"} 1070
telemt_user_octets_from_client{user="hello"} 29310512816 (27.30 GB)
telemt_user_octets_to_client{user="hello"} 863095071076 (803.82 GB)
telemt_user_unique_ips_current{user="hello"} 463
telemt_user_unique_ips_recent_window{user="hello"} 82
```