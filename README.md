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

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
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
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
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

# Server Metrics 2026-03-22 20:35:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 84567.5 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3130385
telemt_connections_bad_total 217797
telemt_connections_current 1089
telemt_connections_me_current 1089
telemt_handshake_timeouts_total 99908
telemt_upstream_connect_attempt_total 30928
telemt_upstream_connect_success_total 30927
telemt_upstream_connect_attempts_per_request{bucket="1"} 30927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20157
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1238
telemt_me_reconnect_success_total 519
telemt_me_reader_eof_total 527
telemt_me_idle_close_by_peer_total 527
telemt_me_route_drop_no_conn_total 2802072
telemt_me_route_drop_channel_closed_total 1116
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2645280
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 653
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 42
telemt_desync_total 11415
telemt_desync_full_logged_total 3585
telemt_desync_suppressed_total 7830
telemt_desync_frames_bucket_total{bucket="1_2"} 3075
telemt_desync_frames_bucket_total{bucket="3_10"} 4195
telemt_desync_frames_bucket_total{bucket="gt_10"} 4145
telemt_pool_swap_total 93
telemt_pool_force_close_total 2907
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 597
telemt_me_draining_writers_reap_progress_total 28293
telemt_me_writer_removed_unexpected_total 511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2060
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26448
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2853
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25386
telemt_me_writer_teardown_success_total{mode="normal"} 28508
telemt_me_writer_teardown_noop_total 28304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56812
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 325.560291
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56812
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 597
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 460
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 2636498
telemt_user_connections_current{user="hello"} 1089
telemt_user_octets_from_client{user="hello"} 38625641048 (35.97 GB)
telemt_user_octets_to_client{user="hello"} 699242438160 (651.22 GB)
telemt_user_unique_ips_current{user="hello"} 463
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 97933.4 (27h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3864040
telemt_connections_bad_total 341177
telemt_connections_current 839
telemt_connections_me_current 839
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98431
telemt_upstream_connect_attempt_total 59141
telemt_upstream_connect_success_total 58416
telemt_upstream_connect_fail_total 640
telemt_upstream_connect_attempts_per_request{bucket="1"} 59056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 640
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6844
telemt_me_reconnect_success_total 2671
telemt_me_reader_eof_total 2620
telemt_me_idle_close_by_peer_total 2620
telemt_me_route_drop_no_conn_total 3614996
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3079893
telemt_me_endpoint_quarantine_total 749
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 754
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 12393
telemt_desync_full_logged_total 6930
telemt_desync_suppressed_total 5463
telemt_desync_frames_bucket_total{bucket="1_2"} 2823
telemt_desync_frames_bucket_total{bucket="3_10"} 4855
telemt_desync_frames_bucket_total{bucket="gt_10"} 4715
telemt_pool_swap_total 91
telemt_pool_force_close_total 2772
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 39035
telemt_me_writer_removed_unexpected_total 2563
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4787
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36831
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 425
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36263
telemt_me_writer_teardown_success_total{mode="normal"} 41618
telemt_me_writer_teardown_noop_total 39036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.262532
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2354
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 3090627
telemt_user_connections_current{user="hello"} 839
telemt_user_octets_from_client{user="hello"} 40563223855 (37.78 GB)
telemt_user_octets_to_client{user="hello"} 743844016566 (692.76 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 172793.5 (47h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16015950
telemt_connections_bad_total 1553476
telemt_connections_current 1864
telemt_connections_me_current 1864
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 393608
telemt_upstream_connect_attempt_total 76628
telemt_upstream_connect_success_total 76530
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 76547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36765
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1689
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2813
telemt_me_reconnect_success_total 1449
telemt_me_reader_eof_total 1392
telemt_me_idle_close_by_peer_total 1390
telemt_me_route_drop_no_conn_total 13993743
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12762033
telemt_me_endpoint_quarantine_total 1092
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1285
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 52681
telemt_desync_full_logged_total 16598
telemt_desync_suppressed_total 36083
telemt_desync_frames_bucket_total{bucket="1_2"} 11733
telemt_desync_frames_bucket_total{bucket="3_10"} 20513
telemt_desync_frames_bucket_total{bucket="gt_10"} 20435
telemt_pool_swap_total 186
telemt_pool_force_close_total 6280
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1019
telemt_me_draining_writers_reap_progress_total 56743
telemt_me_writer_removed_unexpected_total 1344
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4961
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52403
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5810
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50463
telemt_me_writer_teardown_success_total{mode="normal"} 57364
telemt_me_writer_teardown_noop_total 56794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114158
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.747349
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114158
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1019
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1251
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 12762458
telemt_user_connections_current{user="hello"} 1864
telemt_user_octets_from_client{user="hello"} 186994575657 (174.15 GB)
telemt_user_octets_to_client{user="hello"} 3405890219651 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 811
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 172795.0 (47h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11593118
telemt_connections_bad_total 1164132
telemt_connections_current 1291
telemt_connections_me_current 1291
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343280
telemt_upstream_connect_attempt_total 89149
telemt_upstream_connect_success_total 87877
telemt_upstream_connect_fail_total 850
telemt_upstream_connect_attempts_per_request{bucket="1"} 88727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3730
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 850
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4164
telemt_me_reconnect_success_total 1744
telemt_me_reader_eof_total 1610
telemt_me_idle_close_by_peer_total 1610
telemt_me_route_drop_no_conn_total 4512236
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8635905
telemt_me_endpoint_quarantine_total 1090
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1307
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 38289
telemt_desync_full_logged_total 12878
telemt_desync_suppressed_total 25411
telemt_desync_frames_bucket_total{bucket="1_2"} 9444
telemt_desync_frames_bucket_total{bucket="3_10"} 14730
telemt_desync_frames_bucket_total{bucket="gt_10"} 14115
telemt_pool_swap_total 183
telemt_pool_force_close_total 5670
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 704
telemt_me_draining_writers_reap_progress_total 55122
telemt_me_writer_removed_unexpected_total 1648
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5084
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51533
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5161
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49452
telemt_me_writer_teardown_success_total{mode="normal"} 56617
telemt_me_writer_teardown_noop_total 55147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111764
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.758650
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111764
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 704
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1490
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8573978
telemt_user_connections_current{user="hello"} 1291
telemt_user_octets_from_client{user="hello"} 215582449001 (200.78 GB)
telemt_user_octets_to_client{user="hello"} 3876187591102 (3.53 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 524
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 172759.7 (47h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10865865
telemt_connections_bad_total 941356
telemt_connections_current 888
telemt_connections_me_current 888
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344276
telemt_upstream_connect_attempt_total 74370
telemt_upstream_connect_success_total 73161
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 73348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1386
telemt_me_reconnect_attempts_total 5110
telemt_me_reconnect_success_total 2056
telemt_me_reader_eof_total 1795
telemt_me_idle_close_by_peer_total 1794
telemt_me_route_drop_no_conn_total 5287302
telemt_me_route_drop_channel_closed_total 379
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8220434
telemt_me_endpoint_quarantine_total 1175
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1264
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 64
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
telemt_desync_total 37645
telemt_desync_full_logged_total 12458
telemt_desync_suppressed_total 25187
telemt_desync_frames_bucket_total{bucket="1_2"} 9522
telemt_desync_frames_bucket_total{bucket="3_10"} 14382
telemt_desync_frames_bucket_total{bucket="gt_10"} 13741
telemt_pool_swap_total 181
telemt_pool_force_close_total 5609
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 55246
telemt_me_writer_removed_unexpected_total 1937
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5576
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51528
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5058
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49637
telemt_me_writer_teardown_success_total{mode="normal"} 57104
telemt_me_writer_teardown_noop_total 55317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112421
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.030583
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112421
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 1764
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 8212549
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 191305933873 (178.17 GB)
telemt_user_octets_to_client{user="hello"} 3417667823589 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 43038.8 (11h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10889873
telemt_connections_bad_total 660625
telemt_connections_current 1749
telemt_connections_me_current 1749
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 237871
telemt_upstream_connect_attempt_total 46028
telemt_upstream_connect_success_total 43731
telemt_upstream_connect_fail_total 1563
telemt_upstream_connect_attempts_per_request{bucket="1"} 45294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1563
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6637
telemt_me_reconnect_success_total 934
telemt_me_reader_eof_total 590
telemt_me_idle_close_by_peer_total 590
telemt_me_route_drop_no_conn_total 25220640
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9045849
telemt_me_endpoint_quarantine_total 281
telemt_me_single_endpoint_outage_enter_total 66
telemt_me_single_endpoint_outage_exit_total 66
telemt_me_single_endpoint_outage_reconnect_attempt_total 118
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 118
telemt_me_single_endpoint_shadow_rotate_total 335
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 42
telemt_desync_total 14895
telemt_desync_full_logged_total 3947
telemt_desync_suppressed_total 10948
telemt_desync_frames_bucket_total{bucket="1_2"} 2803
telemt_desync_frames_bucket_total{bucket="3_10"} 6043
telemt_desync_frames_bucket_total{bucket="gt_10"} 6049
telemt_pool_swap_total 43
telemt_pool_force_close_total 1563
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 438
telemt_me_draining_writers_reap_progress_total 12355
telemt_me_writer_removed_unexpected_total 832
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11314
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1261
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10792
telemt_me_writer_teardown_success_total{mode="normal"} 13138
telemt_me_writer_teardown_noop_total 12374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25512
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.900767
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25512
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 438
telemt_me_refill_failed_total 315
telemt_me_writer_restored_same_endpoint_total 627
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 9067913
telemt_user_connections_current{user="hello"} 1749
telemt_user_octets_from_client{user="hello"} 83764252139 (78.01 GB)
telemt_user_octets_to_client{user="hello"} 515775452839 (480.35 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 676
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 172765.2 (47h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10755425
telemt_connections_bad_total 908445
telemt_connections_current 1444
telemt_connections_me_current 1444
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 236760
telemt_upstream_connect_attempt_total 103748
telemt_upstream_connect_success_total 102660
telemt_upstream_connect_fail_total 929
telemt_upstream_connect_attempts_per_request{bucket="1"} 103589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 929
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72418
telemt_me_reconnect_success_total 2840
telemt_me_reader_eof_total 2531
telemt_me_idle_close_by_peer_total 2529
telemt_me_route_drop_no_conn_total 5211728
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8497031
telemt_me_endpoint_quarantine_total 1139
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1290
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_me_writers_active_current 47
telemt_desync_total 45276
telemt_desync_full_logged_total 15437
telemt_desync_suppressed_total 29839
telemt_desync_frames_bucket_total{bucket="1_2"} 9174
telemt_desync_frames_bucket_total{bucket="3_10"} 17355
telemt_desync_frames_bucket_total{bucket="gt_10"} 18747
telemt_pool_swap_total 176
telemt_pool_force_close_total 5255
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 642
telemt_me_draining_writers_reap_progress_total 59210
telemt_me_writer_removed_unexpected_total 2569
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6274
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55531
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4528
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 727
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53955
telemt_me_writer_teardown_success_total{mode="normal"} 61805
telemt_me_writer_teardown_noop_total 59211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121016
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.063511
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121016
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 642
telemt_me_refill_failed_total 4286
telemt_me_writer_restored_same_endpoint_total 2389
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 8500267
telemt_user_connections_current{user="hello"} 1444
telemt_user_octets_from_client{user="hello"} 192216212581 (179.02 GB)
telemt_user_octets_to_client{user="hello"} 3234634634448 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 591
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 109601.4 (30h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11353618
telemt_connections_bad_total 455126
telemt_connections_current 1100
telemt_connections_me_current 1100
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4660424
telemt_upstream_connect_attempt_total 51862
telemt_upstream_connect_success_total 51473
telemt_upstream_connect_fail_total 379
telemt_upstream_connect_attempts_per_request{bucket="1"} 51852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 379
telemt_me_reconnect_attempts_total 48589
telemt_me_reconnect_success_total 1681
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1338
telemt_me_route_drop_no_conn_total 4047909
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5473325
telemt_me_endpoint_quarantine_total 707
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 826
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30774
telemt_desync_full_logged_total 10444
telemt_desync_suppressed_total 20330
telemt_desync_frames_bucket_total{bucket="1_2"} 6124
telemt_desync_frames_bucket_total{bucket="3_10"} 12178
telemt_desync_frames_bucket_total{bucket="gt_10"} 12472
telemt_pool_swap_total 115
telemt_pool_force_close_total 3510
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 355
telemt_me_draining_writers_reap_progress_total 38199
telemt_me_writer_removed_unexpected_total 1399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36271
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3069
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34689
telemt_me_writer_teardown_success_total{mode="normal"} 39632
telemt_me_writer_teardown_noop_total 38206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77838
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.529757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77838
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 355
telemt_me_refill_failed_total 2726
telemt_me_writer_restored_same_endpoint_total 1493
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5466098
telemt_user_connections_current{user="hello"} 1100
telemt_user_octets_from_client{user="hello"} 117484051604 (109.42 GB)
telemt_user_octets_to_client{user="hello"} 2096240648018 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 90572.7 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1372436
telemt_connections_bad_total 33742
telemt_connections_current 867
telemt_connections_me_current 867
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25536
telemt_upstream_connect_attempt_total 42734
telemt_upstream_connect_success_total 42603
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 42707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 735
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2020
telemt_me_reconnect_success_total 824
telemt_me_reader_eof_total 804
telemt_me_idle_close_by_peer_total 804
telemt_me_route_drop_no_conn_total 479407
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1216842
telemt_me_endpoint_quarantine_total 746
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 746
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 7336
telemt_desync_full_logged_total 2281
telemt_desync_suppressed_total 5055
telemt_desync_frames_bucket_total{bucket="1_2"} 1610
telemt_desync_frames_bucket_total{bucket="3_10"} 2868
telemt_desync_frames_bucket_total{bucket="gt_10"} 2858
telemt_pool_swap_total 97
telemt_pool_force_close_total 2522
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 35618
telemt_me_writer_removed_unexpected_total 775
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2815
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33610
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33096
telemt_me_writer_teardown_success_total{mode="normal"} 36425
telemt_me_writer_teardown_noop_total 35622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72047
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.539775
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72047
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 66
telemt_me_writer_restored_same_endpoint_total 698
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 1212892
telemt_user_connections_current{user="hello"} 867
telemt_user_octets_from_client{user="hello"} 23359690765 (21.76 GB)
telemt_user_octets_to_client{user="hello"} 513482655007 (478.22 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 172770.0 (47h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13072485
telemt_connections_bad_total 1529928
telemt_connections_current 1354
telemt_connections_me_current 1354
telemt_handshake_timeouts_total 374903
telemt_upstream_connect_attempt_total 65378
telemt_upstream_connect_success_total 65046
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 65243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2565
telemt_me_reconnect_success_total 1342
telemt_me_reader_eof_total 1308
telemt_me_idle_close_by_peer_total 1308
telemt_me_route_drop_no_conn_total 4429528
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9892197
telemt_me_endpoint_quarantine_total 1162
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1292
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 46
telemt_desync_total 41005
telemt_desync_full_logged_total 13371
telemt_desync_suppressed_total 27634
telemt_desync_frames_bucket_total{bucket="1_2"} 9790
telemt_desync_frames_bucket_total{bucket="3_10"} 15133
telemt_desync_frames_bucket_total{bucket="gt_10"} 16082
telemt_pool_swap_total 191
telemt_pool_force_close_total 5248
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 58909
telemt_me_writer_removed_unexpected_total 1259
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4795
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55412
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5074
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53661
telemt_me_writer_teardown_success_total{mode="normal"} 60207
telemt_me_writer_teardown_noop_total 58911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.477527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119118
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1174
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9859830
telemt_user_connections_current{user="hello"} 1354
telemt_user_octets_from_client{user="hello"} 192526081372 (179.30 GB)
telemt_user_octets_to_client{user="hello"} 4359419360028 (3.96 TB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 172766.4 (47h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11374238
telemt_connections_bad_total 1288057
telemt_connections_current 1116
telemt_connections_me_current 1116
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 299462
telemt_upstream_connect_attempt_total 91840
telemt_upstream_connect_success_total 91011
telemt_upstream_connect_fail_total 622
telemt_upstream_connect_attempts_per_request{bucket="1"} 91633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 622
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9866
telemt_me_reconnect_success_total 2378
telemt_me_reader_eof_total 2219
telemt_me_idle_close_by_peer_total 2218
telemt_me_seq_mismatch_total 79
telemt_me_route_drop_no_conn_total 5606059
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8795992
telemt_me_endpoint_quarantine_total 1322
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1291
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 47
telemt_desync_total 40279
telemt_desync_full_logged_total 13011
telemt_desync_suppressed_total 27268
telemt_desync_frames_bucket_total{bucket="1_2"} 10058
telemt_desync_frames_bucket_total{bucket="3_10"} 14954
telemt_desync_frames_bucket_total{bucket="gt_10"} 15267
telemt_pool_swap_total 181
telemt_pool_force_close_total 5046
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 638
telemt_me_draining_writers_reap_progress_total 58682
telemt_me_writer_removed_unexpected_total 2251
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6145
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54864
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53636
telemt_me_writer_teardown_success_total{mode="normal"} 61009
telemt_me_writer_teardown_noop_total 58687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119696
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.188774
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119696
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 638
telemt_me_refill_failed_total 386
telemt_me_writer_restored_same_endpoint_total 1936
telemt_me_writer_restored_fallback_total 109
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 8801512
telemt_user_connections_current{user="hello"} 1116
telemt_user_octets_from_client{user="hello"} 155819041889 (145.12 GB)
telemt_user_octets_to_client{user="hello"} 3410358190135 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 472
telemt_user_unique_ips_recent_window{user="hello"} 136
```