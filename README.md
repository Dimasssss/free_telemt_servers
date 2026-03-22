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

# Server Metrics 2026-03-22 03:52:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 24368.4 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375275
telemt_connections_bad_total 24275
telemt_connections_current 1079
telemt_connections_me_current 1079
telemt_handshake_timeouts_total 20671
telemt_upstream_connect_attempt_total 10212
telemt_upstream_connect_success_total 10211
telemt_upstream_connect_attempts_per_request{bucket="1"} 10211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6552
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 283
telemt_me_reconnect_success_total 156
telemt_me_reader_eof_total 152
telemt_me_idle_close_by_peer_total 152
telemt_me_route_drop_no_conn_total 73146
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310435
telemt_me_endpoint_quarantine_total 192
telemt_me_single_endpoint_shadow_rotate_total 204
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_warm_current 31
telemt_desync_total 2847
telemt_desync_full_logged_total 773
telemt_desync_suppressed_total 2074
telemt_desync_frames_bucket_total{bucket="1_2"} 975
telemt_desync_frames_bucket_total{bucket="3_10"} 1076
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 26
telemt_pool_force_close_total 682
telemt_me_writer_close_signal_drop_total 49
telemt_me_draining_writers_reap_progress_total 9198
telemt_me_writer_removed_unexpected_total 150
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 610
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8730
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 677
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8516
telemt_me_writer_teardown_success_total{mode="normal"} 9340
telemt_me_writer_teardown_noop_total 9199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18539
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.545051
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18539
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 49
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 309715
telemt_user_connections_current{user="hello"} 1079
telemt_user_octets_from_client{user="hello"} 4022479024 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 106627429784 (99.30 GB)
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 37734.4 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 844871
telemt_connections_bad_total 55612
telemt_connections_current 816
telemt_connections_me_current 816
telemt_handshake_timeouts_total 30553
telemt_upstream_connect_attempt_total 17656
telemt_upstream_connect_success_total 17386
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 17632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_reconnect_attempts_total 1493
telemt_me_reconnect_success_total 542
telemt_me_reader_eof_total 480
telemt_me_idle_close_by_peer_total 480
telemt_me_route_drop_no_conn_total 350514
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668526
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 305
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 2847
telemt_desync_full_logged_total 1641
telemt_desync_suppressed_total 1206
telemt_desync_frames_bucket_total{bucket="1_2"} 599
telemt_desync_frames_bucket_total{bucket="3_10"} 1081
telemt_desync_frames_bucket_total{bucket="gt_10"} 1167
telemt_pool_swap_total 40
telemt_pool_force_close_total 1076
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 15660
telemt_me_writer_removed_unexpected_total 457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1296
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14831
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1054
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14584
telemt_me_writer_teardown_success_total{mode="normal"} 16127
telemt_me_writer_teardown_noop_total 15660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31787
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.796662
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31787
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 402
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 667549
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 10884490728 (10.14 GB)
telemt_user_octets_to_client{user="hello"} 238637492452 (222.25 GB)
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 112594.4 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7898702
telemt_connections_bad_total 655158
telemt_connections_current 2462
telemt_connections_me_current 2462
telemt_handshake_timeouts_total 260097
telemt_upstream_connect_attempt_total 42015
telemt_upstream_connect_success_total 41938
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 41945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22779
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1622
telemt_me_reconnect_success_total 841
telemt_me_reader_eof_total 850
telemt_me_idle_close_by_peer_total 850
telemt_me_route_drop_no_conn_total 4560494
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6380492
telemt_me_endpoint_quarantine_total 724
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 842
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_warm_current 40
telemt_desync_total 26790
telemt_desync_full_logged_total 8895
telemt_desync_suppressed_total 17895
telemt_desync_frames_bucket_total{bucket="1_2"} 5784
telemt_desync_frames_bucket_total{bucket="3_10"} 10468
telemt_desync_frames_bucket_total{bucket="gt_10"} 10538
telemt_pool_swap_total 121
telemt_pool_force_close_total 3991
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 612
telemt_me_draining_writers_reap_progress_total 38300
telemt_me_writer_removed_unexpected_total 818
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3185
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35468
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34309
telemt_me_writer_teardown_success_total{mode="normal"} 38653
telemt_me_writer_teardown_noop_total 38344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76997
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 162.402401
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76997
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 612
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 749
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6372503
telemt_user_connections_current{user="hello"} 2462
telemt_user_octets_from_client{user="hello"} 108655233864 (101.19 GB)
telemt_user_octets_to_client{user="hello"} 2135439032368 (1.94 TB)
telemt_user_unique_ips_current{user="hello"} 1194
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 112595.6 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6532636
telemt_connections_bad_total 592686
telemt_connections_current 2186
telemt_connections_me_current 2186
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 217036
telemt_upstream_connect_attempt_total 45972
telemt_upstream_connect_success_total 45578
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 45775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22406
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1967
telemt_me_reconnect_success_total 898
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 2277908
telemt_me_route_drop_channel_closed_total 273
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4870942
telemt_me_endpoint_quarantine_total 705
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 866
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_warm_current 40
telemt_desync_total 22934
telemt_desync_full_logged_total 7818
telemt_desync_suppressed_total 15116
telemt_desync_frames_bucket_total{bucket="1_2"} 5512
telemt_desync_frames_bucket_total{bucket="3_10"} 8906
telemt_desync_frames_bucket_total{bucket="gt_10"} 8516
telemt_pool_swap_total 122
telemt_pool_force_close_total 3619
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 36759
telemt_me_writer_removed_unexpected_total 854
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3042
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34509
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33140
telemt_me_writer_teardown_success_total{mode="normal"} 37551
telemt_me_writer_teardown_noop_total 36765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74316
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.473376
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74316
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 785
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4792987
telemt_user_connections_current{user="hello"} 2186
telemt_user_octets_from_client{user="hello"} 142257356285 (132.49 GB)
telemt_user_octets_to_client{user="hello"} 2273585604283 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1044
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 112560.1 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6403828
telemt_connections_bad_total 550836
telemt_connections_current 1766
telemt_connections_me_current 1766
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 209362
telemt_upstream_connect_attempt_total 52066
telemt_upstream_connect_success_total 51653
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 51792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23851
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2185
telemt_me_reconnect_success_total 941
telemt_me_reader_eof_total 889
telemt_me_idle_close_by_peer_total 889
telemt_me_route_drop_no_conn_total 2196925
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4757121
telemt_me_endpoint_quarantine_total 794
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 840
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_warm_current 12
telemt_desync_total 22788
telemt_desync_full_logged_total 7685
telemt_desync_suppressed_total 15103
telemt_desync_frames_bucket_total{bucket="1_2"} 5558
telemt_desync_frames_bucket_total{bucket="3_10"} 8734
telemt_desync_frames_bucket_total{bucket="gt_10"} 8496
telemt_pool_swap_total 121
telemt_pool_force_close_total 3507
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 37814
telemt_me_writer_removed_unexpected_total 860
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3138
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35553
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3292
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34307
telemt_me_writer_teardown_success_total{mode="normal"} 38691
telemt_me_writer_teardown_noop_total 37826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76517
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.171357
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76517
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 815
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 4752304
telemt_user_connections_current{user="hello"} 1766
telemt_user_octets_from_client{user="hello"} 135071240971 (125.79 GB)
telemt_user_octets_to_client{user="hello"} 2180551690503 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 783
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 112598.9 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20646391
telemt_connections_bad_total 1690997
telemt_connections_current 2662
telemt_connections_me_current 2662
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 621845
telemt_upstream_connect_attempt_total 202840
telemt_upstream_connect_success_total 184559
telemt_upstream_connect_fail_total 16468
telemt_upstream_connect_attempts_per_request{bucket="1"} 201027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8949
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16468
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65128
telemt_me_reconnect_success_total 2401
telemt_me_reader_eof_total 1487
telemt_me_idle_close_by_peer_total 1486
telemt_me_route_drop_no_conn_total 39552029
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16639449
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 876
telemt_me_single_endpoint_outage_enter_total 143
telemt_me_single_endpoint_outage_exit_total 143
telemt_me_single_endpoint_outage_reconnect_attempt_total 296
telemt_me_single_endpoint_outage_reconnect_success_total 75
telemt_me_single_endpoint_quarantine_bypass_total 296
telemt_me_single_endpoint_shadow_rotate_total 884
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 67
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
telemt_me_writers_warm_current 37
telemt_desync_total 32248
telemt_desync_full_logged_total 9703
telemt_desync_suppressed_total 22545
telemt_desync_frames_bucket_total{bucket="1_2"} 6992
telemt_desync_frames_bucket_total{bucket="3_10"} 14304
telemt_desync_frames_bucket_total{bucket="gt_10"} 10952
telemt_pool_swap_total 116
telemt_pool_force_close_total 3741
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 827
telemt_me_draining_writers_reap_progress_total 35307
telemt_me_writer_removed_unexpected_total 2230
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4766
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32512
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3216
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 525
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31566
telemt_me_writer_teardown_success_total{mode="normal"} 37278
telemt_me_writer_teardown_noop_total 35334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72612
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 216.533946
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72612
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 827
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1630
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 16774297
telemt_user_connections_current{user="hello"} 2662
telemt_user_octets_from_client{user="hello"} 232270819848 (216.32 GB)
telemt_user_octets_to_client{user="hello"} 1251012356771 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1203
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 112566.3 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6167112
telemt_connections_bad_total 597665
telemt_connections_current 1992
telemt_connections_me_current 1992
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 129967
telemt_upstream_connect_attempt_total 60827
telemt_upstream_connect_success_total 60132
telemt_upstream_connect_fail_total 594
telemt_upstream_connect_attempts_per_request{bucket="1"} 60726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 594
telemt_me_reconnect_attempts_total 69757
telemt_me_reconnect_success_total 1820
telemt_me_reader_eof_total 1603
telemt_me_idle_close_by_peer_total 1602
telemt_me_route_drop_no_conn_total 2408529
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4787590
telemt_me_endpoint_quarantine_total 762
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 852
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_warm_current 23
telemt_desync_total 23931
telemt_desync_full_logged_total 8398
telemt_desync_suppressed_total 15533
telemt_desync_frames_bucket_total{bucket="1_2"} 4638
telemt_desync_frames_bucket_total{bucket="3_10"} 9264
telemt_desync_frames_bucket_total{bucket="gt_10"} 10029
telemt_pool_swap_total 116
telemt_pool_force_close_total 3320
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 39822
telemt_me_writer_removed_unexpected_total 1640
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4044
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37450
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2919
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36502
telemt_me_writer_teardown_success_total{mode="normal"} 41494
telemt_me_writer_teardown_noop_total 39823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.227428
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 4210
telemt_me_writer_restored_same_endpoint_total 1528
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4780280
telemt_user_connections_current{user="hello"} 1992
telemt_user_octets_from_client{user="hello"} 126111134692 (117.45 GB)
telemt_user_octets_to_client{user="hello"} 1960047300250 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 935
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 49402.1 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4100929
telemt_connections_bad_total 174042
telemt_connections_current 1571
telemt_connections_me_current 1571
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1651307
telemt_upstream_connect_attempt_total 29544
telemt_upstream_connect_success_total 29353
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 29537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_reconnect_attempts_total 45961
telemt_me_reconnect_success_total 998
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 684
telemt_me_route_drop_no_conn_total 1039008
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2004968
telemt_me_endpoint_quarantine_total 366
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 382
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10774
telemt_desync_full_logged_total 3731
telemt_desync_suppressed_total 7043
telemt_desync_frames_bucket_total{bucket="1_2"} 1980
telemt_desync_frames_bucket_total{bucket="3_10"} 4128
telemt_desync_frames_bucket_total{bucket="gt_10"} 4666
telemt_pool_swap_total 53
telemt_pool_force_close_total 1568
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 18395
telemt_me_writer_removed_unexpected_total 757
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1618
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17561
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16827
telemt_me_writer_teardown_success_total{mode="normal"} 19179
telemt_me_writer_teardown_noop_total 18397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.504937
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 892
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2008456
telemt_user_connections_current{user="hello"} 1571
telemt_user_octets_from_client{user="hello"} 55326051764 (51.53 GB)
telemt_user_octets_to_client{user="hello"} 853748753318 (795.12 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 30373.2 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216208
telemt_connections_bad_total 1800
telemt_connections_current 343
telemt_connections_me_current 343
telemt_handshake_timeouts_total 5867
telemt_upstream_connect_attempt_total 14685
telemt_upstream_connect_success_total 14650
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 14683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 337
telemt_me_reconnect_success_total 195
telemt_me_reader_eof_total 199
telemt_me_idle_close_by_peer_total 199
telemt_me_route_drop_no_conn_total 59789
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191089
telemt_me_endpoint_quarantine_total 292
telemt_me_single_endpoint_shadow_rotate_total 264
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1096
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 812
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 33
telemt_pool_force_close_total 737
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 13263
telemt_me_writer_removed_unexpected_total 192
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 845
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12617
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12526
telemt_me_writer_teardown_success_total{mode="normal"} 13462
telemt_me_writer_teardown_noop_total 13263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26725
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.070941
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26725
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 176
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 190757
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 3325365584 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 116696114096 (108.68 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 112570.8 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7484392
telemt_connections_bad_total 753615
telemt_connections_current 2053
telemt_connections_me_current 2053
telemt_handshake_timeouts_total 213638
telemt_upstream_connect_attempt_total 44346
telemt_upstream_connect_success_total 44184
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 44309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_reconnect_attempts_total 1638
telemt_me_reconnect_success_total 871
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 2147936
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5577170
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 866
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_me_writers_warm_current 19
telemt_desync_total 21859
telemt_desync_full_logged_total 7176
telemt_desync_suppressed_total 14683
telemt_desync_frames_bucket_total{bucket="1_2"} 5493
telemt_desync_frames_bucket_total{bucket="3_10"} 7917
telemt_desync_frames_bucket_total{bucket="gt_10"} 8449
telemt_pool_swap_total 124
telemt_pool_force_close_total 3311
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 39990
telemt_me_writer_removed_unexpected_total 826
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3117
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37721
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3223
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36679
telemt_me_writer_teardown_success_total{mode="normal"} 40838
telemt_me_writer_teardown_noop_total 39992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80830
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.696664
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80830
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 779
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 5552069
telemt_user_connections_current{user="hello"} 2053
telemt_user_octets_from_client{user="hello"} 110763730904 (103.16 GB)
telemt_user_octets_to_client{user="hello"} 2587098502756 (2.35 TB)
telemt_user_unique_ips_current{user="hello"} 938
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 112567.2 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6483904
telemt_connections_bad_total 637318
telemt_connections_current 1870
telemt_connections_me_current 1870
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 175312
telemt_upstream_connect_attempt_total 60152
telemt_upstream_connect_success_total 59701
telemt_upstream_connect_fail_total 392
telemt_upstream_connect_attempts_per_request{bucket="1"} 60093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 392
telemt_me_reconnect_attempts_total 5613
telemt_me_reconnect_success_total 1211
telemt_me_reader_eof_total 1094
telemt_me_idle_close_by_peer_total 1094
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2200252
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4943471
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 860
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_warm_current 19
telemt_desync_total 20479
telemt_desync_full_logged_total 6834
telemt_desync_suppressed_total 13645
telemt_desync_frames_bucket_total{bucket="1_2"} 5229
telemt_desync_frames_bucket_total{bucket="3_10"} 7480
telemt_desync_frames_bucket_total{bucket="gt_10"} 7770
telemt_pool_swap_total 122
telemt_pool_force_close_total 3265
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 38547
telemt_me_writer_removed_unexpected_total 1106
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36055
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35282
telemt_me_writer_teardown_success_total{mode="normal"} 39708
telemt_me_writer_teardown_noop_total 38551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78259
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.166389
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78259
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 946
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4946364
telemt_user_connections_current{user="hello"} 1870
telemt_user_octets_from_client{user="hello"} 93244417797 (86.84 GB)
telemt_user_octets_to_client{user="hello"} 2115930652408 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 866
telemt_user_unique_ips_recent_window{user="hello"} 200
```