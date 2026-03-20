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

# Server Metrics 2026-03-20 08:54:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 56220.2 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1268810
telemt_connections_bad_total 68971
telemt_connections_current 1892
telemt_connections_me_current 1892
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 33266
telemt_upstream_connect_attempt_total 10821
telemt_upstream_connect_success_total 10707
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 10821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 6849
telemt_me_reconnect_success_total 6796
telemt_me_reader_eof_total 7191
telemt_me_idle_close_by_peer_total 7189
telemt_me_route_drop_no_conn_total 374325
telemt_me_route_drop_channel_closed_total 196
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1045848
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5316
telemt_desync_full_logged_total 1910
telemt_desync_suppressed_total 3406
telemt_desync_frames_bucket_total{bucket="1_2"} 1097
telemt_desync_frames_bucket_total{bucket="3_10"} 2065
telemt_desync_frames_bucket_total{bucket="gt_10"} 2154
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 100
telemt_me_writer_removed_unexpected_total 6867
telemt_me_writer_restored_same_endpoint_total 6783
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1045400
telemt_user_connections_current{user="hello"} 1892
telemt_user_octets_from_client{user="hello"} 39140362848 (36.45 GB)
telemt_user_octets_to_client{user="hello"} 354239872641 (329.91 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 642
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 72675.6 (20h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5411138
telemt_connections_bad_total 479699
telemt_connections_current 3910
telemt_connections_me_current 3910
telemt_handshake_timeouts_total 113294
telemt_upstream_connect_attempt_total 13386
telemt_upstream_connect_success_total 13101
telemt_upstream_connect_fail_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 13386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 285
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12554
telemt_me_reconnect_success_total 8273
telemt_me_reader_eof_total 8853
telemt_me_idle_close_by_peer_total 8852
telemt_me_route_drop_no_conn_total 3235196
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4459523
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16568
telemt_desync_full_logged_total 5523
telemt_desync_suppressed_total 11045
telemt_desync_frames_bucket_total{bucket="1_2"} 3294
telemt_desync_frames_bucket_total{bucket="3_10"} 6464
telemt_desync_frames_bucket_total{bucket="gt_10"} 6810
telemt_pool_swap_total 64
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 117
telemt_me_writer_removed_unexpected_total 8525
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8218
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 4461676
telemt_user_connections_current{user="hello"} 3910
telemt_user_octets_from_client{user="hello"} 60729380298 (56.56 GB)
telemt_user_octets_to_client{user="hello"} 1493872842594 (1.36 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1406
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 6017.5 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344927
telemt_connections_bad_total 27598
telemt_connections_current 2800
telemt_connections_me_current 2800
telemt_handshake_timeouts_total 3874
telemt_upstream_connect_attempt_total 1220
telemt_upstream_connect_success_total 1220
telemt_upstream_connect_attempts_per_request{bucket="1"} 1220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 842
telemt_me_reconnect_success_total 831
telemt_me_reader_eof_total 814
telemt_me_idle_close_by_peer_total 814
telemt_me_route_drop_no_conn_total 117516
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283391
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1321
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 877
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 456
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 818
telemt_me_writer_restored_same_endpoint_total 831
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 283623
telemt_user_connections_current{user="hello"} 2800
telemt_user_octets_from_client{user="hello"} 4516066088 (4.21 GB)
telemt_user_octets_to_client{user="hello"} 114043991979 (106.21 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1050
telemt_user_unique_ips_recent_window{user="hello"} 401
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 72641.6 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6609582
telemt_connections_bad_total 320441
telemt_connections_current 5165
telemt_connections_me_current 5165
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 88849
telemt_upstream_connect_attempt_total 83001
telemt_upstream_connect_success_total 71241
telemt_upstream_connect_fail_total 11760
telemt_upstream_connect_attempts_per_request{bucket="1"} 83001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11760
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11411
telemt_me_reconnect_success_total 8271
telemt_me_reader_eof_total 8624
telemt_me_idle_close_by_peer_total 8622
telemt_me_route_drop_no_conn_total 9590986
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5684224
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
telemt_desync_total 14743
telemt_desync_full_logged_total 4261
telemt_desync_suppressed_total 10482
telemt_desync_frames_bucket_total{bucket="1_2"} 3294
telemt_desync_frames_bucket_total{bucket="3_10"} 5899
telemt_desync_frames_bucket_total{bucket="gt_10"} 5550
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 835
telemt_me_writer_removed_unexpected_total 9117
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8267
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 846
telemt_user_connections_total{user="hello"} 5743650
telemt_user_connections_current{user="hello"} 5165
telemt_user_octets_from_client{user="hello"} 52859232191 (49.23 GB)
telemt_user_octets_to_client{user="hello"} 918215431009 (855.15 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1571
telemt_user_unique_ips_recent_window{user="hello"} 799
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 10224.5 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2238732
telemt_connections_bad_total 158671
telemt_connections_current 6037
telemt_connections_me_current 6037
telemt_handshake_timeouts_total 26707
telemt_upstream_connect_attempt_total 1775
telemt_upstream_connect_success_total 1763
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 859
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 1208
telemt_me_reconnect_success_total 1205
telemt_me_reader_eof_total 1232
telemt_me_idle_close_by_peer_total 1231
telemt_me_route_drop_no_conn_total 3529242
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1912077
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3990
telemt_desync_full_logged_total 1166
telemt_desync_suppressed_total 2824
telemt_desync_frames_bucket_total{bucket="1_2"} 756
telemt_desync_frames_bucket_total{bucket="3_10"} 1623
telemt_desync_frames_bucket_total{bucket="gt_10"} 1611
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 1210
telemt_me_writer_restored_same_endpoint_total 1175
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1906888
telemt_user_connections_current{user="hello"} 6037
telemt_user_octets_from_client{user="hello"} 16570030564 (15.43 GB)
telemt_user_octets_to_client{user="hello"} 243624295472 (226.89 GB)
telemt_user_unique_ips_current{user="hello"} 1871
telemt_user_unique_ips_recent_window{user="hello"} 1035
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 10159.9 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161639
telemt_connections_bad_total 21164
telemt_connections_current 712
telemt_connections_me_current 712
telemt_handshake_timeouts_total 1763
telemt_upstream_connect_attempt_total 1899
telemt_upstream_connect_success_total 1884
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 925
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 1334
telemt_me_reconnect_success_total 1324
telemt_me_reader_eof_total 1388
telemt_me_idle_close_by_peer_total 1388
telemt_me_route_drop_no_conn_total 85581
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151642
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 1339
telemt_me_writer_restored_same_endpoint_total 1316
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 130846
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 1870809480 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 51710759308 (48.16 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 72606.3 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3631618
telemt_connections_bad_total 234337
telemt_connections_current 5668
telemt_connections_me_current 5668
telemt_handshake_timeouts_total 74368
telemt_upstream_connect_attempt_total 12685
telemt_upstream_connect_success_total 12606
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 12685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9064
telemt_me_reconnect_success_total 9002
telemt_me_reader_eof_total 9519
telemt_me_idle_close_by_peer_total 9519
telemt_me_route_drop_no_conn_total 1302285
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3058664
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14700
telemt_desync_full_logged_total 4907
telemt_desync_suppressed_total 9793
telemt_desync_frames_bucket_total{bucket="1_2"} 2910
telemt_desync_frames_bucket_total{bucket="3_10"} 5315
telemt_desync_frames_bucket_total{bucket="gt_10"} 6475
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 9136
telemt_me_writer_restored_same_endpoint_total 8985
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 3056639
telemt_user_connections_current{user="hello"} 5668
telemt_user_octets_from_client{user="hello"} 63321491116 (58.97 GB)
telemt_user_octets_to_client{user="hello"} 1566277168416 (1.42 TB)
telemt_user_unique_ips_current{user="hello"} 1804
telemt_user_unique_ips_recent_window{user="hello"} 716
```