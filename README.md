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

# Server Metrics 2026-03-22 02:20:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 18857.8 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270715
telemt_connections_bad_total 18676
telemt_connections_current 793
telemt_connections_me_current 793
telemt_handshake_timeouts_total 15635
telemt_upstream_connect_attempt_total 7824
telemt_upstream_connect_success_total 7823
telemt_upstream_connect_attempts_per_request{bucket="1"} 7823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 250
telemt_me_reconnect_success_total 124
telemt_me_reader_eof_total 122
telemt_me_idle_close_by_peer_total 122
telemt_me_route_drop_no_conn_total 49924
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221996
telemt_me_endpoint_quarantine_total 154
telemt_me_single_endpoint_shadow_rotate_total 157
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 1957
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1421
telemt_desync_frames_bucket_total{bucket="1_2"} 623
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 20
telemt_pool_force_close_total 520
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 7032
telemt_me_writer_removed_unexpected_total 122
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 492
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6652
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6512
telemt_me_writer_teardown_success_total{mode="normal"} 7144
telemt_me_writer_teardown_noop_total 7033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14177
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.322455
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14177
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 113
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 221595
telemt_user_connections_current{user="hello"} 793
telemt_user_octets_from_client{user="hello"} 2494625664 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 80840922132 (75.29 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 32224.0 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 771837
telemt_connections_bad_total 45065
telemt_connections_current 646
telemt_connections_me_current 646
telemt_handshake_timeouts_total 28500
telemt_upstream_connect_attempt_total 14922
telemt_upstream_connect_success_total 14683
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 14899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_reconnect_attempts_total 1259
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 413
telemt_me_idle_close_by_peer_total 413
telemt_me_route_drop_no_conn_total 339057
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614089
telemt_me_endpoint_quarantine_total 304
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 260
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
telemt_me_writers_active_current 47
telemt_desync_total 2681
telemt_desync_full_logged_total 1536
telemt_desync_suppressed_total 1145
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 1021
telemt_desync_frames_bucket_total{bucket="gt_10"} 1093
telemt_pool_swap_total 34
telemt_pool_force_close_total 933
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 13208
telemt_me_writer_removed_unexpected_total 392
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1111
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12497
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12275
telemt_me_writer_teardown_success_total{mode="normal"} 13608
telemt_me_writer_teardown_noop_total 13208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26816
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.655674
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26816
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 346
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 613190
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 10052511996 (9.36 GB)
telemt_user_octets_to_client{user="hello"} 218300386484 (203.31 GB)
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 107083.9 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7701610
telemt_connections_bad_total 626312
telemt_connections_current 2034
telemt_connections_me_current 2034
telemt_handshake_timeouts_total 253081
telemt_upstream_connect_attempt_total 39572
telemt_upstream_connect_success_total 39498
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 39505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1561
telemt_me_reconnect_success_total 801
telemt_me_reader_eof_total 810
telemt_me_idle_close_by_peer_total 810
telemt_me_route_drop_no_conn_total 4531097
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6240120
telemt_me_endpoint_quarantine_total 686
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 800
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26356
telemt_desync_full_logged_total 8722
telemt_desync_suppressed_total 17634
telemt_desync_frames_bucket_total{bucket="1_2"} 5684
telemt_desync_frames_bucket_total{bucket="3_10"} 10287
telemt_desync_frames_bucket_total{bucket="gt_10"} 10385
telemt_pool_swap_total 115
telemt_pool_force_close_total 3833
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 600
telemt_me_draining_writers_reap_progress_total 36113
telemt_me_writer_removed_unexpected_total 779
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3008
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33428
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32280
telemt_me_writer_teardown_success_total{mode="normal"} 36436
telemt_me_writer_teardown_noop_total 36157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72593
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 157.472286
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72593
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 600
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 711
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6232297
telemt_user_connections_current{user="hello"} 2034
telemt_user_octets_from_client{user="hello"} 106145428496 (98.86 GB)
telemt_user_octets_to_client{user="hello"} 2070883416368 (1.88 TB)
telemt_user_unique_ips_current{user="hello"} 969
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 107085.2 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6352531
telemt_connections_bad_total 585867
telemt_connections_current 1512
telemt_connections_me_current 1512
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 209997
telemt_upstream_connect_attempt_total 43574
telemt_upstream_connect_success_total 43187
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 43377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1937
telemt_me_reconnect_success_total 867
telemt_me_reader_eof_total 839
telemt_me_idle_close_by_peer_total 839
telemt_me_route_drop_no_conn_total 2252525
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4753420
telemt_me_endpoint_quarantine_total 664
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 821
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
telemt_me_writers_active_current 43
telemt_desync_total 22512
telemt_desync_full_logged_total 7657
telemt_desync_suppressed_total 14855
telemt_desync_frames_bucket_total{bucket="1_2"} 5422
telemt_desync_frames_bucket_total{bucket="3_10"} 8739
telemt_desync_frames_bucket_total{bucket="gt_10"} 8351
telemt_pool_swap_total 116
telemt_pool_force_close_total 3471
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 34608
telemt_me_writer_removed_unexpected_total 824
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2913
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3258
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31137
telemt_me_writer_teardown_success_total{mode="normal"} 35369
telemt_me_writer_teardown_noop_total 34614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69983
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.266436
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69983
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4675615
telemt_user_connections_current{user="hello"} 1512
telemt_user_octets_from_client{user="hello"} 139959362505 (130.35 GB)
telemt_user_octets_to_client{user="hello"} 2203592737379 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 107049.4 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6237408
telemt_connections_bad_total 546465
telemt_connections_current 1499
telemt_connections_me_current 1499
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 201921
telemt_upstream_connect_attempt_total 49812
telemt_upstream_connect_success_total 49446
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 49582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22506
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1970
telemt_me_reconnect_success_total 897
telemt_me_reader_eof_total 840
telemt_me_idle_close_by_peer_total 840
telemt_me_route_drop_no_conn_total 2146001
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4646846
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 799
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 22381
telemt_desync_full_logged_total 7518
telemt_desync_suppressed_total 14863
telemt_desync_frames_bucket_total{bucket="1_2"} 5462
telemt_desync_frames_bucket_total{bucket="3_10"} 8572
telemt_desync_frames_bucket_total{bucket="gt_10"} 8347
telemt_pool_swap_total 115
telemt_pool_force_close_total 3344
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 35867
telemt_me_writer_removed_unexpected_total 812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2973
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33720
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3129
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32523
telemt_me_writer_teardown_success_total{mode="normal"} 36693
telemt_me_writer_teardown_noop_total 35879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72572
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.553928
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72572
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 779
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4642497
telemt_user_connections_current{user="hello"} 1499
telemt_user_octets_from_client{user="hello"} 133440638283 (124.28 GB)
telemt_user_octets_to_client{user="hello"} 2121783322099 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 730
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 107088.7 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20350918
telemt_connections_bad_total 1601577
telemt_connections_current 2105
telemt_connections_me_current 2105
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 601937
telemt_upstream_connect_attempt_total 194923
telemt_upstream_connect_success_total 176956
telemt_upstream_connect_fail_total 16227
telemt_upstream_connect_attempts_per_request{bucket="1"} 193183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8914
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16227
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64839
telemt_me_reconnect_success_total 2300
telemt_me_reader_eof_total 1436
telemt_me_idle_close_by_peer_total 1435
telemt_me_route_drop_no_conn_total 39501329
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16466139
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 838
telemt_me_single_endpoint_outage_enter_total 134
telemt_me_single_endpoint_outage_exit_total 134
telemt_me_single_endpoint_outage_reconnect_attempt_total 284
telemt_me_single_endpoint_outage_reconnect_success_total 69
telemt_me_single_endpoint_quarantine_bypass_total 284
telemt_me_single_endpoint_shadow_rotate_total 837
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 63
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
telemt_desync_total 31891
telemt_desync_full_logged_total 9553
telemt_desync_suppressed_total 22338
telemt_desync_frames_bucket_total{bucket="1_2"} 6910
telemt_desync_frames_bucket_total{bucket="3_10"} 14153
telemt_desync_frames_bucket_total{bucket="gt_10"} 10828
telemt_pool_swap_total 110
telemt_pool_force_close_total 3601
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 792
telemt_me_draining_writers_reap_progress_total 33487
telemt_me_writer_removed_unexpected_total 2136
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4514
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30848
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29886
telemt_me_writer_teardown_success_total{mode="normal"} 35362
telemt_me_writer_teardown_noop_total 33513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68875
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.659385
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68875
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 792
telemt_me_refill_failed_total 3801
telemt_me_writer_restored_same_endpoint_total 1577
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 16595654
telemt_user_connections_current{user="hello"} 2105
telemt_user_octets_from_client{user="hello"} 214631727646 (199.89 GB)
telemt_user_octets_to_client{user="hello"} 1188361545679 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 1022
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 107056.1 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5992604
telemt_connections_bad_total 560863
telemt_connections_current 1505
telemt_connections_me_current 1505
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 125546
telemt_upstream_connect_attempt_total 58351
telemt_upstream_connect_success_total 57674
telemt_upstream_connect_fail_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 58254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 580
telemt_me_reconnect_attempts_total 69643
telemt_me_reconnect_success_total 1781
telemt_me_reader_eof_total 1559
telemt_me_idle_close_by_peer_total 1558
telemt_me_route_drop_no_conn_total 2384904
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4677291
telemt_me_endpoint_quarantine_total 720
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 808
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
telemt_desync_total 23291
telemt_desync_full_logged_total 8205
telemt_desync_suppressed_total 15086
telemt_desync_frames_bucket_total{bucket="1_2"} 4428
telemt_desync_frames_bucket_total{bucket="3_10"} 9017
telemt_desync_frames_bucket_total{bucket="gt_10"} 9846
telemt_pool_swap_total 110
telemt_pool_force_close_total 3179
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 393
telemt_me_draining_writers_reap_progress_total 37601
telemt_me_writer_removed_unexpected_total 1598
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3880
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35349
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34422
telemt_me_writer_teardown_success_total{mode="normal"} 39229
telemt_me_writer_teardown_noop_total 37602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76831
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.115752
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76831
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 393
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1493
telemt_me_writer_restored_fallback_total 33
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4670167
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 124138571944 (115.61 GB)
telemt_user_octets_to_client{user="hello"} 1906845192878 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 745
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 43892.0 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3880290
telemt_connections_bad_total 140819
telemt_connections_current 1190
telemt_connections_me_current 1190
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1581897
telemt_upstream_connect_attempt_total 26837
telemt_upstream_connect_success_total 26663
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 26829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 45806
telemt_me_reconnect_success_total 953
telemt_me_reader_eof_total 635
telemt_me_idle_close_by_peer_total 635
telemt_me_route_drop_no_conn_total 1018544
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1904264
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 336
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10394
telemt_desync_full_logged_total 3584
telemt_desync_suppressed_total 6810
telemt_desync_frames_bucket_total{bucket="1_2"} 1860
telemt_desync_frames_bucket_total{bucket="3_10"} 3987
telemt_desync_frames_bucket_total{bucket="gt_10"} 4547
telemt_pool_swap_total 47
telemt_pool_force_close_total 1446
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 15938
telemt_me_writer_removed_unexpected_total 709
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15177
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1240
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14492
telemt_me_writer_teardown_success_total{mode="normal"} 16673
telemt_me_writer_teardown_noop_total 15940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32613
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.436040
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32613
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 854
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1907916
telemt_user_connections_current{user="hello"} 1190
telemt_user_octets_from_client{user="hello"} 53743235256 (50.05 GB)
telemt_user_octets_to_client{user="hello"} 813325538622 (757.47 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 667
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 24862.9 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191559
telemt_connections_bad_total 1638
telemt_connections_current 337
telemt_connections_me_current 337
telemt_handshake_timeouts_total 5279
telemt_upstream_connect_attempt_total 11904
telemt_upstream_connect_success_total 11876
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 240
telemt_me_reconnect_success_total 155
telemt_me_reader_eof_total 158
telemt_me_idle_close_by_peer_total 158
telemt_me_route_drop_no_conn_total 52330
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168839
telemt_me_endpoint_quarantine_total 247
telemt_me_single_endpoint_shadow_rotate_total 219
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_me_writers_active_current 45
telemt_desync_total 1012
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 756
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 27
telemt_pool_force_close_total 604
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 10739
telemt_me_writer_removed_unexpected_total 152
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 704
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10193
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 602
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10135
telemt_me_writer_teardown_success_total{mode="normal"} 10897
telemt_me_writer_teardown_noop_total 10739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21636
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.966337
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21636
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 141
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 168529
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 3060473796 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 101736641784 (94.75 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 107060.5 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7289240
telemt_connections_bad_total 740099
telemt_connections_current 1676
telemt_connections_me_current 1676
telemt_handshake_timeouts_total 207678
telemt_upstream_connect_attempt_total 41833
telemt_upstream_connect_success_total 41677
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 41796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 1575
telemt_me_reconnect_success_total 841
telemt_me_reader_eof_total 824
telemt_me_idle_close_by_peer_total 824
telemt_me_route_drop_no_conn_total 2122742
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5457979
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 823
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
telemt_me_writers_active_current 43
telemt_desync_total 21425
telemt_desync_full_logged_total 7025
telemt_desync_suppressed_total 14400
telemt_desync_frames_bucket_total{bucket="1_2"} 5386
telemt_desync_frames_bucket_total{bucket="3_10"} 7748
telemt_desync_frames_bucket_total{bucket="gt_10"} 8291
telemt_pool_swap_total 118
telemt_pool_force_close_total 3169
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 37720
telemt_me_writer_removed_unexpected_total 795
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2974
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35560
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3081
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34551
telemt_me_writer_teardown_success_total{mode="normal"} 38534
telemt_me_writer_teardown_noop_total 37722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76256
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.635134
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76256
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 751
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5433041
telemt_user_connections_current{user="hello"} 1676
telemt_user_octets_from_client{user="hello"} 109237975356 (101.74 GB)
telemt_user_octets_to_client{user="hello"} 2533164828028 (2.30 TB)
telemt_user_unique_ips_current{user="hello"} 767
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 107057.2 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6288699
telemt_connections_bad_total 621363
telemt_connections_current 1498
telemt_connections_me_current 1498
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 172205
telemt_upstream_connect_attempt_total 57616
telemt_upstream_connect_success_total 57187
telemt_upstream_connect_fail_total 370
telemt_upstream_connect_attempts_per_request{bucket="1"} 57557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22711
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 370
telemt_me_reconnect_attempts_total 5557
telemt_me_reconnect_success_total 1159
telemt_me_reader_eof_total 1043
telemt_me_idle_close_by_peer_total 1043
telemt_me_seq_mismatch_total 47
telemt_me_route_drop_no_conn_total 2175593
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4824861
telemt_me_endpoint_quarantine_total 846
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 818
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
telemt_desync_total 20037
telemt_desync_full_logged_total 6669
telemt_desync_suppressed_total 13368
telemt_desync_frames_bucket_total{bucket="1_2"} 5112
telemt_desync_frames_bucket_total{bucket="3_10"} 7305
telemt_desync_frames_bucket_total{bucket="gt_10"} 7620
telemt_pool_swap_total 116
telemt_pool_force_close_total 3128
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 36271
telemt_me_writer_removed_unexpected_total 1055
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3498
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33878
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2905
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33143
telemt_me_writer_teardown_success_total{mode="normal"} 37376
telemt_me_writer_teardown_noop_total 36275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73651
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.072442
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73651
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 905
telemt_me_writer_restored_fallback_total 60
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4827925
telemt_user_connections_current{user="hello"} 1498
telemt_user_octets_from_client{user="hello"} 91030429681 (84.78 GB)
telemt_user_octets_to_client{user="hello"} 2062920169376 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 728
telemt_user_unique_ips_recent_window{user="hello"} 152
```