# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
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

## rdp-onedash.ru (2 сервера)
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

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-21 12:29:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 57246.5 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1858008
telemt_connections_bad_total 91834
telemt_connections_current 1587
telemt_connections_me_current 1587
telemt_handshake_timeouts_total 70021
telemt_upstream_connect_attempt_total 22237
telemt_upstream_connect_success_total 22126
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 22198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14186
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1178
telemt_me_reconnect_success_total 508
telemt_me_reader_eof_total 490
telemt_me_idle_close_by_peer_total 490
telemt_me_route_drop_no_conn_total 1415467
telemt_me_route_drop_channel_closed_total 455
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1456148
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 406
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 454
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 41
telemt_desync_total 5603
telemt_desync_full_logged_total 1969
telemt_desync_suppressed_total 3634
telemt_desync_frames_bucket_total{bucket="1_2"} 1196
telemt_desync_frames_bucket_total{bucket="3_10"} 2164
telemt_desync_frames_bucket_total{bucket="gt_10"} 2243
telemt_pool_swap_total 62
telemt_pool_force_close_total 1818
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 351
telemt_me_draining_writers_reap_progress_total 19876
telemt_me_writer_removed_unexpected_total 471
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1640
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18559
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1754
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18058
telemt_me_writer_teardown_success_total{mode="normal"} 20199
telemt_me_writer_teardown_noop_total 19880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40079
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 152.617693
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40079
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 351
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 441
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1455094
telemt_user_connections_current{user="hello"} 1587
telemt_user_octets_from_client{user="hello"} 21133937163 (19.68 GB)
telemt_user_octets_to_client{user="hello"} 377794694175 (351.85 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 2891.4 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206605
telemt_connections_bad_total 12898
telemt_connections_current 1640
telemt_connections_me_current 1640
telemt_handshake_timeouts_total 12948
telemt_upstream_connect_attempt_total 1207
telemt_upstream_connect_success_total 1161
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 88
telemt_me_reconnect_success_total 60
telemt_me_reader_eof_total 57
telemt_me_idle_close_by_peer_total 57
telemt_me_route_drop_no_conn_total 190663
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165276
telemt_me_endpoint_quarantine_total 26
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 25
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 609
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 2
telemt_pool_force_close_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 916
telemt_me_writer_removed_unexpected_total 65
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 129
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 852
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 866
telemt_me_writer_teardown_success_total{mode="normal"} 981
telemt_me_writer_teardown_noop_total 916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1897
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.154884
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1897
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_writer_restored_same_endpoint_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 165194
telemt_user_connections_current{user="hello"} 1640
telemt_user_octets_from_client{user="hello"} 2468943308 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 40348254324 (37.58 GB)
telemt_user_unique_ips_current{user="hello"} 849
telemt_user_unique_ips_recent_window{user="hello"} 518
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 57244.3 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3570224
telemt_connections_bad_total 369823
telemt_connections_current 3788
telemt_connections_me_current 3788
telemt_handshake_timeouts_total 140959
telemt_upstream_connect_attempt_total 21724
telemt_upstream_connect_success_total 21691
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 808
telemt_me_reconnect_success_total 447
telemt_me_reader_eof_total 456
telemt_me_idle_close_by_peer_total 456
telemt_me_route_drop_no_conn_total 1714639
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2848678
telemt_me_endpoint_quarantine_total 371
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 439
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 12231
telemt_desync_full_logged_total 4130
telemt_desync_suppressed_total 8101
telemt_desync_frames_bucket_total{bucket="1_2"} 2591
telemt_desync_frames_bucket_total{bucket="3_10"} 4786
telemt_desync_frames_bucket_total{bucket="gt_10"} 4854
telemt_pool_swap_total 61
telemt_pool_force_close_total 1926
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 279
telemt_me_draining_writers_reap_progress_total 19742
telemt_me_writer_removed_unexpected_total 440
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1667
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18336
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1785
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17816
telemt_me_writer_teardown_success_total{mode="normal"} 20003
telemt_me_writer_teardown_noop_total 19757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39760
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.430409
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39760
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 279
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 403
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2844903
telemt_user_connections_current{user="hello"} 3788
telemt_user_octets_from_client{user="hello"} 45810647516 (42.66 GB)
telemt_user_octets_to_client{user="hello"} 1002014602528 (933.20 GB)
telemt_user_unique_ips_current{user="hello"} 1505
telemt_user_unique_ips_recent_window{user="hello"} 565
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 57245.8 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2921084
telemt_connections_bad_total 321063
telemt_connections_current 3569
telemt_connections_me_current 3569
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 116725
telemt_upstream_connect_attempt_total 26452
telemt_upstream_connect_success_total 26180
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 26312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 473
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1138
telemt_me_reconnect_success_total 523
telemt_me_reader_eof_total 485
telemt_me_idle_close_by_peer_total 485
telemt_me_route_drop_no_conn_total 912334
telemt_me_route_drop_channel_closed_total 72
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2082081
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 440
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 9517
telemt_desync_full_logged_total 3246
telemt_desync_suppressed_total 6271
telemt_desync_frames_bucket_total{bucket="1_2"} 2382
telemt_desync_frames_bucket_total{bucket="3_10"} 3697
telemt_desync_frames_bucket_total{bucket="gt_10"} 3438
telemt_pool_swap_total 62
telemt_pool_force_close_total 1735
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 19252
telemt_me_writer_removed_unexpected_total 473
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1629
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18116
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1620
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17517
telemt_me_writer_teardown_success_total{mode="normal"} 19745
telemt_me_writer_teardown_noop_total 19253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38998
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.011111
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38998
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 438
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2083219
telemt_user_connections_current{user="hello"} 3569
telemt_user_octets_from_client{user="hello"} 38996168413 (36.32 GB)
telemt_user_octets_to_client{user="hello"} 990051798367 (922.06 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1398
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 57209.0 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2838825
telemt_connections_bad_total 318522
telemt_connections_current 3393
telemt_connections_me_current 3393
telemt_handshake_timeouts_total 83999
telemt_upstream_connect_attempt_total 23085
telemt_upstream_connect_success_total 22995
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 594
telemt_me_reader_eof_total 543
telemt_me_idle_close_by_peer_total 543
telemt_me_route_drop_no_conn_total 858026
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2065634
telemt_me_endpoint_quarantine_total 424
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 434
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 9604
telemt_desync_full_logged_total 3203
telemt_desync_suppressed_total 6401
telemt_desync_frames_bucket_total{bucket="1_2"} 2514
telemt_desync_frames_bucket_total{bucket="3_10"} 3649
telemt_desync_frames_bucket_total{bucket="gt_10"} 3441
telemt_pool_swap_total 60
telemt_pool_force_close_total 1709
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 189
telemt_me_draining_writers_reap_progress_total 20554
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1707
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19403
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1558
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18845
telemt_me_writer_teardown_success_total{mode="normal"} 21110
telemt_me_writer_teardown_noop_total 20558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41668
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.933014
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41668
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 189
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 519
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 2062525
telemt_user_connections_current{user="hello"} 3393
telemt_user_octets_from_client{user="hello"} 46786981112 (43.57 GB)
telemt_user_octets_to_client{user="hello"} 991849433240 (923.73 GB)
telemt_user_unique_ips_current{user="hello"} 1321
telemt_user_unique_ips_recent_window{user="hello"} 428
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 57248.4 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9347252
telemt_connections_bad_total 645247
telemt_connections_current 5231
telemt_connections_me_current 5231
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 315200
telemt_upstream_connect_attempt_total 88786
telemt_upstream_connect_success_total 83622
telemt_upstream_connect_fail_total 4323
telemt_upstream_connect_attempts_per_request{bucket="1"} 87945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4323
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3477
telemt_me_reconnect_success_total 1173
telemt_me_reader_eof_total 824
telemt_me_idle_close_by_peer_total 823
telemt_me_route_drop_no_conn_total 16729164
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7700967
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 454
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_desync_total 14716
telemt_desync_full_logged_total 4737
telemt_desync_suppressed_total 9979
telemt_desync_frames_bucket_total{bucket="1_2"} 3135
telemt_desync_frames_bucket_total{bucket="3_10"} 6527
telemt_desync_frames_bucket_total{bucket="gt_10"} 5054
telemt_pool_swap_total 58
telemt_pool_force_close_total 1837
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 378
telemt_me_draining_writers_reap_progress_total 18795
telemt_me_writer_removed_unexpected_total 1134
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2438
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17373
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 262
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16958
telemt_me_writer_teardown_success_total{mode="normal"} 19811
telemt_me_writer_teardown_noop_total 18804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.326774
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 378
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 813
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 7758824
telemt_user_connections_current{user="hello"} 5231
telemt_user_octets_from_client{user="hello"} 61279971785 (57.07 GB)
telemt_user_octets_to_client{user="hello"} 682095729396 (635.25 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1922
telemt_user_unique_ips_recent_window{user="hello"} 1000
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 57216.0 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2886479
telemt_connections_bad_total 346844
telemt_connections_current 3813
telemt_connections_me_current 3813
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 63524
telemt_upstream_connect_attempt_total 24649
telemt_upstream_connect_success_total 24377
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 24623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_reconnect_attempts_total 2402
telemt_me_reconnect_success_total 826
telemt_me_reader_eof_total 822
telemt_me_idle_close_by_peer_total 822
telemt_me_route_drop_no_conn_total 1039863
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2178818
telemt_me_endpoint_quarantine_total 358
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 438
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 9994
telemt_desync_full_logged_total 3526
telemt_desync_suppressed_total 6468
telemt_desync_frames_bucket_total{bucket="1_2"} 1962
telemt_desync_frames_bucket_total{bucket="3_10"} 4004
telemt_desync_frames_bucket_total{bucket="gt_10"} 4028
telemt_pool_swap_total 58
telemt_pool_force_close_total 1630
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 20537
telemt_me_writer_removed_unexpected_total 795
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1963
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19396
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1445
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 185
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18907
telemt_me_writer_teardown_success_total{mode="normal"} 21359
telemt_me_writer_teardown_noop_total 20538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41897
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.375552
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41897
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 702
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 2163768
telemt_user_connections_current{user="hello"} 3813
telemt_user_octets_from_client{user="hello"} 40410301812 (37.64 GB)
telemt_user_octets_to_client{user="hello"} 954088096238 (888.56 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1488
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 57210.5 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4338043
telemt_connections_bad_total 222634
telemt_connections_current 3032
telemt_connections_me_current 3032
telemt_handshake_timeouts_total 1894514
telemt_upstream_connect_attempt_total 22923
telemt_upstream_connect_success_total 22889
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 22892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 900
telemt_me_reconnect_success_total 411
telemt_me_reader_eof_total 416
telemt_me_idle_close_by_peer_total 416
telemt_me_route_drop_no_conn_total 939550
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1944419
telemt_me_endpoint_quarantine_total 438
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 450
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 9324
telemt_desync_full_logged_total 3314
telemt_desync_suppressed_total 6010
telemt_desync_frames_bucket_total{bucket="1_2"} 1715
telemt_desync_frames_bucket_total{bucket="3_10"} 3724
telemt_desync_frames_bucket_total{bucket="gt_10"} 3885
telemt_pool_swap_total 62
telemt_pool_force_close_total 1576
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 20515
telemt_me_writer_removed_unexpected_total 400
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1394
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19546
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1523
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18939
telemt_me_writer_teardown_success_total{mode="normal"} 20940
telemt_me_writer_teardown_noop_total 20515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41455
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.225770
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41455
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 359
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1938017
telemt_user_connections_current{user="hello"} 3032
telemt_user_octets_from_client{user="hello"} 35725955992 (33.27 GB)
telemt_user_octets_to_client{user="hello"} 921568976720 (858.28 GB)
telemt_user_unique_ips_current{user="hello"} 1246
telemt_user_unique_ips_recent_window{user="hello"} 478
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 55201.9 (15h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 905824
telemt_connections_bad_total 79533
telemt_connections_current 610
telemt_connections_me_current 610
telemt_handshake_timeouts_total 327429
telemt_upstream_connect_attempt_total 26249
telemt_upstream_connect_success_total 26247
telemt_upstream_connect_attempts_per_request{bucket="1"} 26247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1115
telemt_me_reconnect_success_total 430
telemt_me_reader_eof_total 429
telemt_me_idle_close_by_peer_total 429
telemt_me_route_drop_no_conn_total 192615
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434121
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 469
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 3007
telemt_desync_full_logged_total 1131
telemt_desync_suppressed_total 1876
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 1074
telemt_desync_frames_bucket_total{bucket="gt_10"} 1421
telemt_pool_swap_total 61
telemt_pool_force_close_total 1368
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 94
telemt_me_draining_writers_reap_progress_total 23530
telemt_me_writer_removed_unexpected_total 406
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1715
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22229
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1365
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22162
telemt_me_writer_teardown_success_total{mode="normal"} 23944
telemt_me_writer_teardown_noop_total 23530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47474
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.853488
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47474
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 94
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 433964
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 6858225999 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 165511438445 (154.14 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 57221.6 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3081827
telemt_connections_bad_total 301701
telemt_connections_current 4201
telemt_connections_me_current 4201
telemt_handshake_timeouts_total 88174
telemt_upstream_connect_attempt_total 23758
telemt_upstream_connect_success_total 23658
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 23727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11864
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 965
telemt_me_reconnect_success_total 543
telemt_me_reader_eof_total 507
telemt_me_idle_close_by_peer_total 507
telemt_me_route_drop_no_conn_total 832738
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2424647
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 445
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 9838
telemt_desync_full_logged_total 3232
telemt_desync_suppressed_total 6606
telemt_desync_frames_bucket_total{bucket="1_2"} 2356
telemt_desync_frames_bucket_total{bucket="3_10"} 3669
telemt_desync_frames_bucket_total{bucket="gt_10"} 3813
telemt_pool_swap_total 63
telemt_pool_force_close_total 1597
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 166
telemt_me_draining_writers_reap_progress_total 21332
telemt_me_writer_removed_unexpected_total 498
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1649
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20198
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1569
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19735
telemt_me_writer_teardown_success_total{mode="normal"} 21847
telemt_me_writer_teardown_noop_total 21332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.294206
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 166
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 483
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 2417785
telemt_user_connections_current{user="hello"} 4201
telemt_user_octets_from_client{user="hello"} 51098356860 (47.59 GB)
telemt_user_octets_to_client{user="hello"} 1131519272824 (1.03 TB)
telemt_user_unique_ips_current{user="hello"} 1554
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 57217.3 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2791046
telemt_connections_bad_total 234339
telemt_connections_current 3481
telemt_connections_me_current 3481
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 78088
telemt_upstream_connect_attempt_total 39906
telemt_upstream_connect_success_total 39649
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 39863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_reconnect_attempts_total 3409
telemt_me_reconnect_success_total 721
telemt_me_reader_eof_total 623
telemt_me_idle_close_by_peer_total 623
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 889100
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2240238
telemt_me_endpoint_quarantine_total 499
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 443
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 8585
telemt_desync_full_logged_total 2944
telemt_desync_suppressed_total 5641
telemt_desync_frames_bucket_total{bucket="1_2"} 2222
telemt_desync_frames_bucket_total{bucket="3_10"} 3184
telemt_desync_frames_bucket_total{bucket="gt_10"} 3179
telemt_pool_swap_total 62
telemt_pool_force_close_total 1555
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 20465
telemt_me_writer_removed_unexpected_total 636
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1943
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19186
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1454
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 101
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18910
telemt_me_writer_teardown_success_total{mode="normal"} 21129
telemt_me_writer_teardown_noop_total 20466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41595
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.401342
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41595
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 547
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2250575
telemt_user_connections_current{user="hello"} 3481
telemt_user_octets_from_client{user="hello"} 42009698061 (39.12 GB)
telemt_user_octets_to_client{user="hello"} 986150470868 (918.42 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1343
telemt_user_unique_ips_recent_window{user="hello"} 472
```