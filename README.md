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

# Server Metrics 2026-03-23 06:27:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 120046.4 (33h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4316108
telemt_connections_bad_total 410525
telemt_connections_current 1616
telemt_connections_me_current 1616
telemt_handshake_timeouts_total 147050
telemt_upstream_connect_attempt_total 44539
telemt_upstream_connect_success_total 44538
telemt_upstream_connect_attempts_per_request{bucket="1"} 44538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1554
telemt_me_reconnect_success_total 698
telemt_me_reader_eof_total 722
telemt_me_idle_close_by_peer_total 722
telemt_me_route_drop_no_conn_total 3571347
telemt_me_route_drop_channel_closed_total 1382
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3531118
telemt_me_writer_pick_total{mode="p2c",result="full"} 22
telemt_me_endpoint_quarantine_total 851
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 940
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
telemt_desync_total 14651
telemt_desync_full_logged_total 4646
telemt_desync_suppressed_total 10005
telemt_desync_frames_bucket_total{bucket="1_2"} 3780
telemt_desync_frames_bucket_total{bucket="3_10"} 5471
telemt_desync_frames_bucket_total{bucket="gt_10"} 5400
telemt_pool_swap_total 133
telemt_pool_force_close_total 4102
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 781
telemt_me_draining_writers_reap_progress_total 40827
telemt_me_writer_removed_unexpected_total 694
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2933
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38159
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4031
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36725
telemt_me_writer_teardown_success_total{mode="normal"} 41093
telemt_me_writer_teardown_noop_total 40839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81932
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 451.296047
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81932
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 781
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 626
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 3518321
telemt_user_connections_current{user="hello"} 1616
telemt_user_octets_from_client{user="hello"} 46466156728 (43.27 GB)
telemt_user_octets_to_client{user="hello"} 916831071820 (853.87 GB)
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 133412.9 (37h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4215105
telemt_connections_bad_total 392844
telemt_connections_current 934
telemt_connections_me_current 934
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 111414
telemt_upstream_connect_attempt_total 82825
telemt_upstream_connect_success_total 81827
telemt_upstream_connect_fail_total 885
telemt_upstream_connect_attempts_per_request{bucket="1"} 82712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 885
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11149
telemt_me_reconnect_success_total 4024
telemt_me_reader_eof_total 3993
telemt_me_idle_close_by_peer_total 3992
telemt_me_route_drop_no_conn_total 3686473
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3341830
telemt_me_endpoint_quarantine_total 1085
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1053
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_active_current 87
telemt_me_writers_warm_current 2
telemt_desync_total 13797
telemt_desync_full_logged_total 7788
telemt_desync_suppressed_total 6009
telemt_desync_frames_bucket_total{bucket="1_2"} 3124
telemt_desync_frames_bucket_total{bucket="3_10"} 5415
telemt_desync_frames_bucket_total{bucket="gt_10"} 5258
telemt_pool_swap_total 125
telemt_pool_force_close_total 3492
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 272
telemt_me_draining_writers_reap_progress_total 55966
telemt_me_writer_removed_unexpected_total 3914
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7064
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52860
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52474
telemt_me_writer_teardown_success_total{mode="normal"} 59924
telemt_me_writer_teardown_noop_total 55967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115891
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.026210
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115891
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 272
telemt_me_refill_failed_total 283
telemt_me_writer_restored_same_endpoint_total 3564
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 3356170
telemt_user_connections_current{user="hello"} 934
telemt_user_octets_from_client{user="hello"} 45187882259 (42.08 GB)
telemt_user_octets_to_client{user="hello"} 850364353801 (791.96 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 208273.1 (57h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16816236
telemt_connections_bad_total 1708524
telemt_connections_current 2242
telemt_connections_me_current 2242
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 415456
telemt_upstream_connect_attempt_total 93425
telemt_upstream_connect_success_total 93314
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 93331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1735
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3322
telemt_me_reconnect_success_total 1747
telemt_me_reader_eof_total 1705
telemt_me_idle_close_by_peer_total 1702
telemt_me_route_drop_no_conn_total 14154195
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13356787
telemt_me_endpoint_quarantine_total 1413
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1579
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_me_writers_active_current 89
telemt_desync_total 56071
telemt_desync_full_logged_total 17911
telemt_desync_suppressed_total 38160
telemt_desync_frames_bucket_total{bucket="1_2"} 12460
telemt_desync_frames_bucket_total{bucket="3_10"} 21972
telemt_desync_frames_bucket_total{bucket="gt_10"} 21639
telemt_pool_swap_total 225
telemt_pool_force_close_total 7200
telemt_pool_stale_pick_total 20
telemt_me_writer_close_signal_drop_total 1115
telemt_me_draining_writers_reap_progress_total 72028
telemt_me_writer_removed_unexpected_total 1638
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6076
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66876
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6730
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64828
telemt_me_writer_teardown_success_total{mode="normal"} 72952
telemt_me_writer_teardown_noop_total 72082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145034
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.973690
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145034
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1115
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1518
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13356531
telemt_user_connections_current{user="hello"} 2242
telemt_user_octets_from_client{user="hello"} 202009348729 (188.14 GB)
telemt_user_octets_to_client{user="hello"} 3640002425939 (3.31 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 208274.1 (57h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12281435
telemt_connections_bad_total 1310719
telemt_connections_current 1412
telemt_connections_me_current 1412
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 355965
telemt_upstream_connect_attempt_total 107805
telemt_upstream_connect_success_total 106390
telemt_upstream_connect_fail_total 901
telemt_upstream_connect_attempts_per_request{bucket="1"} 107291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 901
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4767
telemt_me_reconnect_success_total 2056
telemt_me_reader_eof_total 1911
telemt_me_idle_close_by_peer_total 1911
telemt_me_route_drop_no_conn_total 4634097
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9078292
telemt_me_endpoint_quarantine_total 1425
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1595
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_desync_total 39949
telemt_desync_full_logged_total 13514
telemt_desync_suppressed_total 26435
telemt_desync_frames_bucket_total{bucket="1_2"} 9911
telemt_desync_frames_bucket_total{bucket="3_10"} 15327
telemt_desync_frames_bucket_total{bucket="gt_10"} 14711
telemt_pool_swap_total 223
telemt_pool_force_close_total 6583
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 724
telemt_me_draining_writers_reap_progress_total 70196
telemt_me_writer_removed_unexpected_total 1941
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6146
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65854
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6068
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63613
telemt_me_writer_teardown_success_total{mode="normal"} 72000
telemt_me_writer_teardown_noop_total 70221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142221
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 105.114062
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142221
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 724
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1752
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 9015783
telemt_user_connections_current{user="hello"} 1412
telemt_user_octets_from_client{user="hello"} 221121802564 (205.94 GB)
telemt_user_octets_to_client{user="hello"} 4054588914235 (3.69 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 208238.5 (57h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11415789
telemt_connections_bad_total 1051101
telemt_connections_current 1069
telemt_connections_me_current 1069
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 362308
telemt_upstream_connect_attempt_total 92209
telemt_upstream_connect_success_total 90628
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 90833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44734
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5952
telemt_me_reconnect_success_total 2517
telemt_me_reader_eof_total 2254
telemt_me_idle_close_by_peer_total 2253
telemt_me_route_drop_no_conn_total 5403780
telemt_me_route_drop_channel_closed_total 388
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8581341
telemt_me_endpoint_quarantine_total 1478
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1558
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
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
telemt_desync_total 39071
telemt_desync_full_logged_total 12990
telemt_desync_suppressed_total 26081
telemt_desync_frames_bucket_total{bucket="1_2"} 9854
telemt_desync_frames_bucket_total{bucket="3_10"} 14947
telemt_desync_frames_bucket_total{bucket="gt_10"} 14270
telemt_pool_swap_total 219
telemt_pool_force_close_total 6470
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 769
telemt_me_draining_writers_reap_progress_total 70800
telemt_me_writer_removed_unexpected_total 2399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6895
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 577
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64330
telemt_me_writer_teardown_success_total{mode="normal"} 73136
telemt_me_writer_teardown_noop_total 70871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3175.542703
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 769
telemt_me_refill_failed_total 182
telemt_me_writer_restored_same_endpoint_total 2185
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 8573058
telemt_user_connections_current{user="hello"} 1069
telemt_user_octets_from_client{user="hello"} 194870819295 (181.49 GB)
telemt_user_octets_to_client{user="hello"} 3557787668849 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 78517.6 (21h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11868794
telemt_connections_bad_total 722048
telemt_connections_current 2287
telemt_connections_me_current 2287
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 335944
telemt_upstream_connect_attempt_total 72636
telemt_upstream_connect_success_total 68881
telemt_upstream_connect_fail_total 2457
telemt_upstream_connect_attempts_per_request{bucket="1"} 71338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2457
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8650
telemt_me_reconnect_success_total 1613
telemt_me_reader_eof_total 1029
telemt_me_idle_close_by_peer_total 1028
telemt_me_route_drop_no_conn_total 25433306
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9789221
telemt_me_endpoint_quarantine_total 626
telemt_me_single_endpoint_outage_enter_total 113
telemt_me_single_endpoint_outage_exit_total 113
telemt_me_single_endpoint_outage_reconnect_attempt_total 215
telemt_me_single_endpoint_outage_reconnect_success_total 58
telemt_me_single_endpoint_quarantine_bypass_total 215
telemt_me_single_endpoint_shadow_rotate_total 632
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 17588
telemt_desync_full_logged_total 4949
telemt_desync_suppressed_total 12639
telemt_desync_frames_bucket_total{bucket="1_2"} 3421
telemt_desync_frames_bucket_total{bucket="3_10"} 7191
telemt_desync_frames_bucket_total{bucket="gt_10"} 6976
telemt_pool_swap_total 81
telemt_pool_force_close_total 2505
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 550
telemt_me_draining_writers_reap_progress_total 26073
telemt_me_writer_removed_unexpected_total 1483
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24124
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2153
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 352
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23568
telemt_me_writer_teardown_success_total{mode="normal"} 27502
telemt_me_writer_teardown_noop_total 26092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53594
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.484143
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53594
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 550
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 1029
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3157
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 9820340
telemt_user_connections_current{user="hello"} 2287
telemt_user_octets_from_client{user="hello"} 92250496360 (85.91 GB)
telemt_user_octets_to_client{user="hello"} 774284816864 (721.11 GB)
telemt_user_msgs_from_client{user="hello"} 78576
telemt_user_msgs_to_client{user="hello"} 74228
telemt_user_unique_ips_current{user="hello"} 753
telemt_user_unique_ips_recent_window{user="hello"} 634
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 208244.2 (57h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11413308
telemt_connections_bad_total 1007376
telemt_connections_current 1357
telemt_connections_me_current 1357
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 260319
telemt_upstream_connect_attempt_total 121530
telemt_upstream_connect_success_total 120233
telemt_upstream_connect_fail_total 1118
telemt_upstream_connect_attempts_per_request{bucket="1"} 121351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1118
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73759
telemt_me_reconnect_success_total 3360
telemt_me_reader_eof_total 3037
telemt_me_idle_close_by_peer_total 3034
telemt_me_route_drop_no_conn_total 5354175
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8980843
telemt_me_endpoint_quarantine_total 1431
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1586
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 47708
telemt_desync_full_logged_total 16421
telemt_desync_suppressed_total 31287
telemt_desync_frames_bucket_total{bucket="1_2"} 9707
telemt_desync_frames_bucket_total{bucket="3_10"} 18284
telemt_desync_frames_bucket_total{bucket="gt_10"} 19717
telemt_pool_swap_total 214
telemt_pool_force_close_total 6170
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 75166
telemt_me_writer_removed_unexpected_total 3053
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7474
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70793
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5400
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 770
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68996
telemt_me_writer_teardown_success_total{mode="normal"} 78267
telemt_me_writer_teardown_noop_total 75167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 152682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153434
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.506351
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153434
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 4327
telemt_me_writer_restored_same_endpoint_total 2828
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7375
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8983398
telemt_user_connections_current{user="hello"} 1357
telemt_user_octets_from_client{user="hello"} 200163573165 (186.42 GB)
telemt_user_octets_to_client{user="hello"} 3441973788236 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 145080.6 (40h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12228017
telemt_connections_bad_total 504902
telemt_connections_current 1419
telemt_connections_me_current 1419
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4923499
telemt_upstream_connect_attempt_total 70244
telemt_upstream_connect_success_total 69741
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 70231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_reconnect_attempts_total 49487
telemt_me_reconnect_success_total 2010
telemt_me_reader_eof_total 1691
telemt_me_idle_close_by_peer_total 1690
telemt_me_route_drop_no_conn_total 4169831
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5875321
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1117
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
telemt_me_writers_active_current 41
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 33090
telemt_desync_full_logged_total 11353
telemt_desync_suppressed_total 21737
telemt_desync_frames_bucket_total{bucket="1_2"} 6655
telemt_desync_frames_bucket_total{bucket="3_10"} 13021
telemt_desync_frames_bucket_total{bucket="gt_10"} 13414
telemt_pool_swap_total 155
telemt_pool_force_close_total 4334
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 399
telemt_me_draining_writers_reap_progress_total 54876
telemt_me_writer_removed_unexpected_total 1726
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4358
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52304
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3888
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 446
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50542
telemt_me_writer_teardown_success_total{mode="normal"} 56662
telemt_me_writer_teardown_noop_total 54883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111545
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.944854
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111545
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 399
telemt_me_refill_failed_total 2758
telemt_me_writer_restored_same_endpoint_total 1774
telemt_me_writer_restored_fallback_total 31
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4336
telemt_user_connections_total{user="hello"} 5867144
telemt_user_connections_current{user="hello"} 1419
telemt_user_octets_from_client{user="hello"} 122724449420 (114.30 GB)
telemt_user_octets_to_client{user="hello"} 2289223480882 (2.08 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 617
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 126051.2 (35h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1801810
telemt_connections_bad_total 37740
telemt_connections_current 1128
telemt_connections_me_current 1128
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 39899
telemt_upstream_connect_attempt_total 59008
telemt_upstream_connect_success_total 58811
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 58969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 869
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 2562
telemt_me_reconnect_success_total 1036
telemt_me_reader_eof_total 1034
telemt_me_idle_close_by_peer_total 1034
telemt_me_route_drop_no_conn_total 688074
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1601422
telemt_me_endpoint_quarantine_total 1067
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1036
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 17
telemt_desync_total 10704
telemt_desync_full_logged_total 3024
telemt_desync_suppressed_total 7680
telemt_desync_frames_bucket_total{bucket="1_2"} 3406
telemt_desync_frames_bucket_total{bucket="3_10"} 4002
telemt_desync_frames_bucket_total{bucket="gt_10"} 3296
telemt_pool_swap_total 136
telemt_pool_force_close_total 3443
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 50347
telemt_me_writer_removed_unexpected_total 996
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3796
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47595
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3355
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46904
telemt_me_writer_teardown_success_total{mode="normal"} 51391
telemt_me_writer_teardown_noop_total 50351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101742
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.745611
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101742
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 889
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1596948
telemt_user_connections_current{user="hello"} 1128
telemt_user_octets_from_client{user="hello"} 28354619293 (26.41 GB)
telemt_user_octets_to_client{user="hello"} 628546208655 (585.38 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 208249.2 (57h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13698025
telemt_connections_bad_total 1667543
telemt_connections_current 1592
telemt_connections_me_current 1592
telemt_handshake_timeouts_total 401660
telemt_upstream_connect_attempt_total 84093
telemt_upstream_connect_success_total 83724
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 83956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3307
telemt_me_reconnect_success_total 1654
telemt_me_reader_eof_total 1646
telemt_me_idle_close_by_peer_total 1646
telemt_me_route_drop_no_conn_total 4556119
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10324884
telemt_me_endpoint_quarantine_total 1545
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1585
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 43478
telemt_desync_full_logged_total 14152
telemt_desync_suppressed_total 29326
telemt_desync_frames_bucket_total{bucket="1_2"} 10561
telemt_desync_frames_bucket_total{bucket="3_10"} 15992
telemt_desync_frames_bucket_total{bucket="gt_10"} 16925
telemt_pool_swap_total 231
telemt_pool_force_close_total 6017
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 76133
telemt_me_writer_removed_unexpected_total 1573
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5849
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71920
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5843
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70116
telemt_me_writer_teardown_success_total{mode="normal"} 77769
telemt_me_writer_teardown_noop_total 76135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 153007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153904
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.197511
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153904
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1453
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10291181
telemt_user_connections_current{user="hello"} 1592
telemt_user_octets_from_client{user="hello"} 197967542312 (184.37 GB)
telemt_user_octets_to_client{user="hello"} 4590808362752 (4.18 TB)
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 208245.9 (57h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12018815
telemt_connections_bad_total 1421943
telemt_connections_current 1512
telemt_connections_me_current 1512
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 322865
telemt_upstream_connect_attempt_total 112133
telemt_upstream_connect_success_total 111172
telemt_upstream_connect_fail_total 752
telemt_upstream_connect_attempts_per_request{bucket="1"} 111924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 752
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11218
telemt_me_reconnect_success_total 2803
telemt_me_reader_eof_total 2600
telemt_me_idle_close_by_peer_total 2599
telemt_me_seq_mismatch_total 113
telemt_me_route_drop_no_conn_total 5726374
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9245242
telemt_me_endpoint_quarantine_total 1735
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1590
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_desync_total 43431
telemt_desync_full_logged_total 13872
telemt_desync_suppressed_total 29559
telemt_desync_frames_bucket_total{bucket="1_2"} 11251
telemt_desync_frames_bucket_total{bucket="3_10"} 16058
telemt_desync_frames_bucket_total{bucket="gt_10"} 16122
telemt_pool_swap_total 221
telemt_pool_force_close_total 5763
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 76653
telemt_me_writer_removed_unexpected_total 2634
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7273
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 72122
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5291
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 472
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70890
telemt_me_writer_teardown_success_total{mode="normal"} 79395
telemt_me_writer_teardown_noop_total 76658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 153290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 155112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 155668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 156003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 156053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 156053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 156053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 156053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 156053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 156053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 156053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 156053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 156053
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.068533
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 156053
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 437
telemt_me_writer_restored_same_endpoint_total 2232
telemt_me_writer_restored_fallback_total 148
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 9249453
telemt_user_connections_current{user="hello"} 1512
telemt_user_octets_from_client{user="hello"} 160600555268 (149.57 GB)
telemt_user_octets_to_client{user="hello"} 3620316173158 (3.29 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 546
telemt_user_unique_ips_recent_window{user="hello"} 211
```