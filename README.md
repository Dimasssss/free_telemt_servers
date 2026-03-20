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

# Server Metrics 2026-03-20 08:49:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 55914.9 (15h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1257252
telemt_connections_bad_total 68486
telemt_connections_current 1740
telemt_connections_me_current 1740
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 33008
telemt_upstream_connect_attempt_total 10765
telemt_upstream_connect_success_total 10651
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 10765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 6793
telemt_me_reconnect_success_total 6740
telemt_me_reader_eof_total 7130
telemt_me_idle_close_by_peer_total 7128
telemt_me_route_drop_no_conn_total 370050
telemt_me_route_drop_channel_closed_total 193
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1036234
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5255
telemt_desync_full_logged_total 1892
telemt_desync_suppressed_total 3363
telemt_desync_frames_bucket_total{bucket="1_2"} 1087
telemt_desync_frames_bucket_total{bucket="3_10"} 2042
telemt_desync_frames_bucket_total{bucket="gt_10"} 2126
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 100
telemt_me_writer_removed_unexpected_total 6811
telemt_me_writer_restored_same_endpoint_total 6727
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1035789
telemt_user_connections_current{user="hello"} 1740
telemt_user_octets_from_client{user="hello"} 38978529272 (36.30 GB)
telemt_user_octets_to_client{user="hello"} 351612014433 (327.46 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 624
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 72370.4 (20h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5379768
telemt_connections_bad_total 472500
telemt_connections_current 3974
telemt_connections_me_current 3974
telemt_handshake_timeouts_total 112822
telemt_upstream_connect_attempt_total 13364
telemt_upstream_connect_success_total 13079
telemt_upstream_connect_fail_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 13364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 285
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12532
telemt_me_reconnect_success_total 8252
telemt_me_reader_eof_total 8830
telemt_me_idle_close_by_peer_total 8829
telemt_me_route_drop_no_conn_total 3224807
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4438129
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16487
telemt_desync_full_logged_total 5493
telemt_desync_suppressed_total 10994
telemt_desync_frames_bucket_total{bucket="1_2"} 3280
telemt_desync_frames_bucket_total{bucket="3_10"} 6432
telemt_desync_frames_bucket_total{bucket="gt_10"} 6775
telemt_pool_swap_total 64
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 117
telemt_me_writer_removed_unexpected_total 8502
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8197
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 4440286
telemt_user_connections_current{user="hello"} 3974
telemt_user_octets_from_client{user="hello"} 60209762130 (56.07 GB)
telemt_user_octets_to_client{user="hello"} 1487231483046 (1.35 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1408
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 5712.4 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324272
telemt_connections_bad_total 26494
telemt_connections_current 2773
telemt_connections_me_current 2773
telemt_handshake_timeouts_total 3571
telemt_upstream_connect_attempt_total 1157
telemt_upstream_connect_success_total 1157
telemt_upstream_connect_attempts_per_request{bucket="1"} 1157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 779
telemt_me_reconnect_success_total 768
telemt_me_reader_eof_total 751
telemt_me_idle_close_by_peer_total 751
telemt_me_route_drop_no_conn_total 109506
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265809
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1248
telemt_desync_full_logged_total 419
telemt_desync_suppressed_total 829
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 436
telemt_desync_frames_bucket_total{bucket="gt_10"} 570
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 755
telemt_me_writer_restored_same_endpoint_total 768
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 266040
telemt_user_connections_current{user="hello"} 2773
telemt_user_octets_from_client{user="hello"} 4238817960 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 106702013519 (99.37 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1049
telemt_user_unique_ips_recent_window{user="hello"} 460
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 72347.9 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4861591
telemt_connections_bad_total 590173
telemt_connections_current 5248
telemt_connections_me_current 5248
telemt_handshake_timeouts_total 71329
telemt_upstream_connect_attempt_total 13035
telemt_upstream_connect_success_total 12926
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 13035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 8823
telemt_me_reconnect_success_total 7854
telemt_me_reader_eof_total 8231
telemt_me_idle_close_by_peer_total 8226
telemt_me_route_drop_no_conn_total 2999984
telemt_me_route_drop_channel_closed_total 302
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3511036
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12215
telemt_desync_full_logged_total 3895
telemt_desync_suppressed_total 8320
telemt_desync_frames_bucket_total{bucket="1_2"} 2873
telemt_desync_frames_bucket_total{bucket="3_10"} 4605
telemt_desync_frames_bucket_total{bucket="gt_10"} 4737
telemt_pool_swap_total 72
telemt_me_writer_close_signal_drop_total 362
telemt_me_writer_removed_unexpected_total 7961
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7853
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 3517400
telemt_user_connections_current{user="hello"} 5248
telemt_user_octets_from_client{user="hello"} 52982419514 (49.34 GB)
telemt_user_octets_to_client{user="hello"} 1315722995792 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1677
telemt_user_unique_ips_recent_window{user="hello"} 662
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 72336.4 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6515797
telemt_connections_bad_total 318847
telemt_connections_current 5498
telemt_connections_me_current 5498
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 87992
telemt_upstream_connect_attempt_total 82982
telemt_upstream_connect_success_total 71223
telemt_upstream_connect_fail_total 11759
telemt_upstream_connect_attempts_per_request{bucket="1"} 82982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11630
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11759
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11392
telemt_me_reconnect_success_total 8253
telemt_me_reader_eof_total 8604
telemt_me_idle_close_by_peer_total 8602
telemt_me_route_drop_no_conn_total 9320752
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5598303
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
telemt_desync_total 14681
telemt_desync_full_logged_total 4238
telemt_desync_suppressed_total 10443
telemt_desync_frames_bucket_total{bucket="1_2"} 3280
telemt_desync_frames_bucket_total{bucket="3_10"} 5870
telemt_desync_frames_bucket_total{bucket="gt_10"} 5531
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 835
telemt_me_writer_removed_unexpected_total 9097
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8249
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 844
telemt_user_connections_total{user="hello"} 5657676
telemt_user_connections_current{user="hello"} 5498
telemt_user_octets_from_client{user="hello"} 52508047263 (48.90 GB)
telemt_user_octets_to_client{user="hello"} 914817457077 (851.99 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1627
telemt_user_unique_ips_recent_window{user="hello"} 947
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 9919.7 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2169170
telemt_connections_bad_total 154556
telemt_connections_current 5700
telemt_connections_me_current 5700
telemt_handshake_timeouts_total 25912
telemt_upstream_connect_attempt_total 1685
telemt_upstream_connect_success_total 1674
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 1162
telemt_me_reconnect_success_total 1159
telemt_me_reader_eof_total 1176
telemt_me_idle_close_by_peer_total 1175
telemt_me_route_drop_no_conn_total 3411172
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1851093
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3852
telemt_desync_full_logged_total 1130
telemt_desync_suppressed_total 2722
telemt_desync_frames_bucket_total{bucket="1_2"} 737
telemt_desync_frames_bucket_total{bucket="3_10"} 1563
telemt_desync_frames_bucket_total{bucket="gt_10"} 1552
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 1164
telemt_me_writer_restored_same_endpoint_total 1129
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1845905
telemt_user_connections_current{user="hello"} 5700
telemt_user_octets_from_client{user="hello"} 16148995908 (15.04 GB)
telemt_user_octets_to_client{user="hello"} 236016824416 (219.81 GB)
telemt_user_unique_ips_current{user="hello"} 1854
telemt_user_unique_ips_recent_window{user="hello"} 743
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 9855.6 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156810
telemt_connections_bad_total 20608
telemt_connections_current 727
telemt_connections_me_current 727
telemt_handshake_timeouts_total 1740
telemt_upstream_connect_attempt_total 1797
telemt_upstream_connect_success_total 1783
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1278
telemt_me_reconnect_success_total 1268
telemt_me_reader_eof_total 1313
telemt_me_idle_close_by_peer_total 1313
telemt_me_route_drop_no_conn_total 83822
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147614
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 474
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 316
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 1283
telemt_me_writer_restored_same_endpoint_total 1260
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 126824
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 1818780864 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 50021465596 (46.59 GB)
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 72301.1 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3592965
telemt_connections_bad_total 230912
telemt_connections_current 5697
telemt_connections_me_current 5697
telemt_handshake_timeouts_total 73265
telemt_upstream_connect_attempt_total 12650
telemt_upstream_connect_success_total 12571
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 12650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5731
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9029
telemt_me_reconnect_success_total 8968
telemt_me_reader_eof_total 9483
telemt_me_idle_close_by_peer_total 9483
telemt_me_route_drop_no_conn_total 1290275
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3025823
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14626
telemt_desync_full_logged_total 4878
telemt_desync_suppressed_total 9748
telemt_desync_frames_bucket_total{bucket="1_2"} 2896
telemt_desync_frames_bucket_total{bucket="3_10"} 5285
telemt_desync_frames_bucket_total{bucket="gt_10"} 6445
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 9100
telemt_me_writer_restored_same_endpoint_total 8951
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 3023807
telemt_user_connections_current{user="hello"} 5697
telemt_user_octets_from_client{user="hello"} 62986456084 (58.66 GB)
telemt_user_octets_to_client{user="hello"} 1552456373548 (1.41 TB)
telemt_user_unique_ips_current{user="hello"} 1794
telemt_user_unique_ips_recent_window{user="hello"} 720
```